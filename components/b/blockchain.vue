<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yol-2xb1x"/><path class="yxynemtcg"/><path class="pbfb4_u0l"/><path class="wahc4hz1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blockchain" /></template>
<style>
.pbfb4_u0l {
  d: path("m2.5 15.5l3.5 2l3.5-2m-3.5 2v4m12-8l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wahc4hz1p {
  d: path("m14.5 15.5l3.5 2l3.5-2m-3.5 2v4M8.5 8L6 13.5M15.5 8l2.5 5.5m-8.5 4h5");
}

.yol-2xb1x {
  d: path("m12 2l3.5 2v4L12 10L8.5 8V4Z");
}

.yxynemtcg {
  d: path("M8.5 4L12 6l3.5-2M12 6v4m-6 3.5l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

</style>
