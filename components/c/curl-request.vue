<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rr-wjzb3t"/><path class="oa1hobbdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curl-request" /></template>
<style>
.oa1hobbdk {
  d: path("M10.25 5.75L12.5 8l-2.25 2.25m5 .75h3.5m-3.5 4h3.5");
}

.rr-wjzb3t {
  d: path("M12.5 4.5a2 2 0 0 1 2-2H18L21.5 6v13.5a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2Zm-10 15c0-6.5 5-2.5 5-8c0-2 .5-3.5 2-3.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
