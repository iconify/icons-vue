<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzxhhr26v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lot-size" /></template>
<style>
.rzxhhr26v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6V3h3m12 0h3v3m0 6v3h-3M6 15H3v-3m7-9h4m-4 12h4M3 8v2m18-2v2M3 19.5h18m-16-2l-2 2l2 2m14-4l2 2l-2 2");
}

</style>
