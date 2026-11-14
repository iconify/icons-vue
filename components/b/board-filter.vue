<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz3exrwxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:board-filter" /></template>
<style>
.vz3exrwxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3za2 2 0 0 1 2 2v13a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m6.75 0za2 2 0 0 1 2 2v6a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m6.75 0za2 2 0 0 1 2 2v3a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m-1.547 12h2.594A.915.915 0 0 1 20 16.5l-.902 1.083a1.5 1.5 0 0 0-.348.96v1.868a.518.518 0 0 1-.75.464a1.36 1.36 0 0 1-.75-1.214v-1.118a1.5 1.5 0 0 0-.348-.96L16 16.5a.915.915 0 0 1 .703-1.5");
}

</style>
