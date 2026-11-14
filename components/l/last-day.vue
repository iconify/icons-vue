<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xfgcv786r"/><path class="jpwdejr7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:last-day" /></template>
<style>
.jpwdejr7r {
  d: path("M17 14.5h-1.75A1.25 1.25 0 0 0 14 15.75v4.5a1.25 1.25 0 0 0 1.25 1.25H17m-.25-3.5h4.75m-2-2l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfgcv786r {
  d: path("M11.2 21H3.5V4.5h17v8.6M8 2.5v4m8-4v4m-12.5 3h17");
}

</style>
