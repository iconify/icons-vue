<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0jbkt1nl"/><path class="wqkmk6bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ev-car-full" /></template>
<style>
.u0jbkt1nl {
  d: path("M5 11.5H2.5v-4l3.5-1l2.5-4h6l3 4l4 1v4H19m-4 0H9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqkmk6bjs {
  d: path("M5 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.5 5h5a1 1 0 0 1 1 1v.75h1v1.5h-1v.75a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Z");
}

</style>
