<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ycq0w_wxw"/><path class="qrtvxhffc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fridge-smart" /></template>
<style>
.qrtvxhffc {
  d: path("M14.75 17.5a5 5 0 0 1 7 0m-5 2a2.25 2.25 0 0 1 3 0m-1.5 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ycq0w_wxw {
  d: path("M14.8 21.5H4v-19h13v10.9M4 10h13M7 5.25v2m0 5.5v4");
}

</style>
