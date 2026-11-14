<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xuooclz3l"/><path class="kojsju5nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coaching-session" /></template>
<style>
.kojsju5nf {
  d: path("M7 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuooclz3l {
  d: path("M9 6.5h11a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-5a6.5 6.5 0 1 1-6-4Z");
}

</style>
