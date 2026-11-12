<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wdhm326bq"/><path class="ahcwsvb2k"/><path class="lgdpnsvji"/><path class="yqmotfmyy"/><path class="b1nxqifcp"/><path class="zy4x83b9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-3-line-duotone" /></template>
<style>
.ahcwsvb2k {
  d: path("M9.6851 21H14.3158C16.5656 21 17.6906 21 18.5044 20.3646C19.3181 19.7292 19.591 18.6379 20.1366 16.4552C20.9946 13.0234 21.4236 11.3075 20.5227 10.1538C19.6219 9 17.8532 9 14.3158 9H9.6851C6.14769 9 4.37899 9 3.47816 10.1538C2.57733 11.3075 3.0063 13.0234 3.86425 16.4552C4.40992 18.6379 4.68275 19.7292 5.49654 20.3646C6.31032 21 7.43525 21 9.6851 21Z");
}

.b1nxqifcp {
  stroke-linejoin: round;
  d: path("M16 13V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgdpnsvji {
  d: path("M10 5H14C14.5523 5 15 4.55228 15 4C15 3.44772 14.5523 3 14 3H10C9.44772 3 9 3.44772 9 4C9 4.55228 9.44772 5 10 5Z");
}

.wdhm326bq {
  d: path("M19.4601 9.39865L18.7892 6.89465C18.5152 5.89005 18.3783 5.38775 18.0974 5.00946C17.8176 4.63273 17.4374 4.34234 17.0003 4.17152C16.5615 4 16.0408 4 14.9996 4M4.53897 9.39861L5.20996 6.89465C5.48389 5.89005 5.62085 5.38775 5.90178 5.00946C6.18156 4.63273 6.56172 4.34234 6.99879 4.17152C7.43765 4 7.95829 4 8.99957 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yqmotfmyy {
  stroke-linejoin: round;
  d: path("M8 13V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zy4x83b9r {
  stroke-linejoin: round;
  d: path("M12 13V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
