dtb-$(CONFIG_ARCH_EXYNOS7) += exynos7-espresso.dtb

ifdef CONFIG_SOC_EXYNOS8895
dtb-$(CONFIG_CAMERA_DREAM) += exynos8895-dreamlte_eur_open_00.dtb exynos8895-dreamlte_eur_open_01.dtb exynos8895-dreamlte_eur_open_02.dtb exynos8895-dreamlte_eur_open_03.dtb exynos8895-dreamlte_eur_open_04.dtb exynos8895-dreamlte_eur_open_05.dtb exynos8895-dreamlte_eur_open_07.dtb exynos8895-dreamlte_eur_open_08.dtb exynos8895-dreamlte_eur_open_09.dtb exynos8895-dreamlte_eur_open_10.dtb
dtb-$(CONFIG_CAMERA_DREAM2) += exynos8895-dream2lte_eur_open_01.dtb exynos8895-dream2lte_eur_open_02.dtb exynos8895-dream2lte_eur_open_03.dtb exynos8895-dream2lte_eur_open_04.dtb exynos8895-dream2lte_eur_open_05.dtb exynos8895-dream2lte_eur_open_06.dtb exynos8895-dream2lte_eur_open_07.dtb exynos8895-dream2lte_eur_open_08.dtb exynos8895-dream2lte_eur_open_09.dtb exynos8895-dream2lte_eur_open_10.dtb
endif

dtb-$(CONFIG_SOC_EMULATOR8895) += emulator8895-emulator8895.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
