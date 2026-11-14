<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5l1uu8rk"/><path class="ydes0-r_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dev-dependency" /></template>
<style>
.k5l1uu8rk {
  d: path("M14.059 16.335L10 18.5l-7.5-4v-8l7.5-4l7.5 4v5.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydes0-r_v {
  d: path("m2.5 6.5l7.5 4l7.5-4m-7.5 4v8M21.75 16a2.5 2.5 0 1 1-2-1.75M17.5 18.5l-3 3");
}

</style>
