<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="knolwxb3m"/><path class="zx_v1ibim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:intruder-alert" /></template>
<style>
.knolwxb3m {
  d: path("M15.244 20H3V10l8.5-7.25L20 10v1.656");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zx_v1ibim {
  d: path("M9.25 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8 20c0-2.5 1.5-4.25 3.5-4.25S15 17.5 15 20m3-5.5V18m0 3h.01");
}

</style>
