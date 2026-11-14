<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5tp7k9ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clearance-rack" /></template>
<style>
.y5tp7k9ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19m-14 0v2m-2 .5h4L12 8l-1.25 1.5l-.75-.75V16H5V8.75l-.75.75L3 8Zm11-2.5v2M14 12.699V8.75l-.75.75L12 8l2.5-2.5h4L21 8l-1.25 1.5l-.75-.75V13h-.701m-3.549 8.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
