<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zziakns7n"/><path class="y26snsc_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-aluminium" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y26snsc_q {
  d: path("M5.5 11.5h9l2.5 6m-2.5-6l4-5");
}

.zziakns7n {
  d: path("m3 17.5l2.5-6l4-5h9l2.5 6l-4 5Z");
}

</style>
