<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cewlzcccs"/><path class="urldrljgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-free" /></template>
<style>
.cewlzcccs {
  d: path("M12.505 17.368L10 18.75l-7.25-4v-8.5l7.25-4l7.25 4v4.72");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urldrljgt {
  d: path("M2.75 6.25L10 10.5l7.25-4.25M10 10.5v8.25m10.75-2.5C20.5 15.5 19.5 15 18 15s-2.75.75-2.75 1.75c0 2.25 5.5 1 5.5 2.75c0 1-1.25 1.5-2.75 1.5s-2.5-.5-2.75-1.25m2.75-6V15m0 6v1m-4 0l8-8");
}

</style>
