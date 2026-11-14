<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kwgk8l3ak"/><path class="p3xmfebiu"/><path class="dqxpcbc2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gable-roof" /></template>
<style>
.dqxpcbc2r {
  d: path("M9.75 14L12 11.75L14.25 14Z");
}

.kwgk8l3ak {
  d: path("M2.5 14L12 4l9.5 10");
}

.p3xmfebiu {
  d: path("M5 21.5V15l7-7.5l7 7.5v6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
