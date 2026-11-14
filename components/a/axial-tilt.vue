<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wqrr0df_f"/><path class="qrr19dwxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:axial-tilt" /></template>
<style>
.qrr19dwxp {
  d: path("M6 12a6 2 0 1 0 12 0a6 2 0 1 0-12 0Zm6-9a9 9 0 0 1 3.5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqrr0df_f {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm9.75-9.25l-7.5 18.5");
}

</style>
