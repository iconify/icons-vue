<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdozbpban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leadership-training" /></template>
<style>
.fdozbpban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.944 17.9l4.628-8.33a1.75 1.75 0 0 1 3.006-.09l.954 1.499A1.174 1.174 0 0 0 14.5 11a1.09 1.09 0 0 1 1.863.083l3.725 6.829a1.75 1.75 0 0 1-1.536 2.588H5.474a1.75 1.75 0 0 1-1.53-2.6M10 7V2.5m1.193.373l.807.252a.655.655 0 0 1 0 1.25l-.807.252A.92.92 0 0 1 10 3.75a.92.92 0 0 1 1.193-.877");
}

</style>
