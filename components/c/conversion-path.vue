<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lylnt0bcq"/><path class="afoxwro0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conversion-path" /></template>
<style>
.afoxwro0d {
  d: path("m19 4.25l2 2l-2 2");
}

.lylnt0bcq {
  d: path("M2.5 19.75H7v-4.5h4.5v-4.5H16v-4.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
