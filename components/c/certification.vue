<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zwz9jvx6z"/><path class="yk31d26nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certification" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk31d26nb {
  d: path("m8.75 14.75l-2 6.75l2-1l1.75 1v-6.25m4.75-.5l2 6.75l-2-1l-1.75 1v-6.25M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.zwz9jvx6z {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

</style>
