<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yn1z8yb6k"/><path class="jsk1r51dd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:content-calendar" /></template>
<style>
.jsk1r51dd {
  d: path("M15.5 14.5h4l2.25 2.25v4.75H15.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yn1z8yb6k {
  d: path("M12.7 21H3.5V4.5h17v7.2M8 2.5v4m8-4v4m-12.5 3h17");
}

</style>
