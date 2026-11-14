<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0u5vq2st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:circle-of-fifths" /></template>
<style>
.n0u5vq2st {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.185 16.19q.495.805 1.163 1.472q.669.667 1.475 1.161m8.294.037q.831-.5 1.52-1.183q.688-.684 1.193-1.512m.022-8.294q-.501-.831-1.186-1.518t-1.514-1.191m-8.294-.006q-.83.502-1.516 1.188T5.154 7.86m7.907 1.701l1.378 1.378a1.5 1.5 0 0 1 0 2.122l-1.378 1.378a1.5 1.5 0 0 1-2.122 0l-1.378-1.378a1.5 1.5 0 0 1 0-2.122l1.378-1.378a1.5 1.5 0 0 1 2.122 0M10.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-8 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-8-8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
