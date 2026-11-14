<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ttsfjubit"/><path class="tx7vg9nnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bullwhip-effect" /></template>
<style>
.ttsfjubit {
  d: path("M2.5 2.5v19h19");
}

.tx7vg9nnx {
  d: path("M5.5 11L8 9.5l2.5 3.5l3-6l3 10L20 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
