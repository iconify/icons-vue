<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0z_pzvrc"/><path class="bmq-ygpux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-plus-corner-duocolor" /></template>
<style>
.bmq-ygpux {
  d: path("m8 20l-5 1l1-5a8.944 8.944 0 1 1 16-8");
}

.m0z_pzvrc {
  stroke-opacity: 0.4;
  d: path("M13 17h8m-4-4v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
