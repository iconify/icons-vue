<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r9a-oiqvi"/><path class="o5lqwu2nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gem-gravel" /></template>
<style>
.o5lqwu2nq {
  d: path("M4.5 20.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0Z");
}

.r9a-oiqvi {
  d: path("M8 3.5h8l3.5 4L12 18L4.5 7.5Zm-3.5 4h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
