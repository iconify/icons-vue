<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wox2grd3a"/><path clip-rule="evenodd" class="ikhz1ibbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guesthouse-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ikhz1ibbr {
  fill-rule: evenodd;
  d: path("M22.86 2L22.998 3.99L21 4.13V17C21 17.55 20.552 18 20 18H4C3.448 18 3 17.55 3 17V5.9L1.199 6.08L1 4.09L3 3.89V2H5V3.69L19.921 2.2L22.86 2ZM11.996 12C10.895 12 10 12.9 10 14V16H14V14C14 12.97 13.217 12.12 12.215 12.01L11.996 12ZM8.065 8C7.516 8 7 8.51 7 9.06C7.054 9.56 7.555 9.99 8.066 10C8.562 9.94 8.997 9.42 9.001 8.91C8.92 8.49 8.502 8.05 8.065 8Z");
}

.wox2grd3a {
  d: path("M15 20V22H9V20H15Z");
}

</style>
