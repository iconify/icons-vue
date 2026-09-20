<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fa9joccbo"/><path class="dmqg6xbxr"/><path class="pwc0rzflc"/><path class="rhtl3vb5u"/><path class="hjz9frcqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lineage-table-outline-thin" /></template>
<style>
.dmqg6xbxr {
  d: path("M2 16a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.fa9joccbo {
  d: path("M2 5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hjz9frcqe {
  d: path("M8.5 17.5H11V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pwc0rzflc {
  d: path("M13.5 10.5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

.rhtl3vb5u {
  d: path("M8.5 6.5H11V12h2.5");
}

</style>
