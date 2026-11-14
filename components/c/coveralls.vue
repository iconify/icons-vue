<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx0qsgb9p"/><path class="zn8hh5egl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coveralls" /></template>
<style>
.bx0qsgb9p {
  d: path("m9.5 3l-4 1l-3 8.5l2.5 1L7 8v13h3.5l1.5-6.5l1.5 6.5H17V8l2 5.5l2.5-1l-3-8.5l-4-1q-2.5 2.5-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zn8hh5egl {
  d: path("M9.75 7.5v4h4.5v-4Z");
}

</style>
