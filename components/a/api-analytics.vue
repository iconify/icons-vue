<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yqo1jsb5p"/><path class="e7maqcb0g"/><path class="olo9et2dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-analytics" /></template>
<style>
.e7maqcb0g {
  d: path("M2.5 7L7 2.5h14.5V17L17 21.5M17 7l4.5-4.5");
}

.olo9et2dz {
  d: path("m5.5 17.5l3-4l2.5 2l3-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqo1jsb5p {
  d: path("M2.5 7H17v14.5H2.5Z");
}

</style>
