<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk694sbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disinfectant-spray" /></template>
<style>
.bk694sbdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 11h2a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 5 17.5v-3A3.5 3.5 0 0 1 8.5 11M7 11V7a2 2 0 0 1 2-2h6v3h-3v3m-2.5 2.75v4.5M7.25 16h4.5m6.75-9.5h.01m2.49-2h.01m-.01 4h.01");
}

</style>
