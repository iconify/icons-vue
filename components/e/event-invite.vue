<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="melkgeemz"/><path class="d96nfgblu"/><path class="t0two85ez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-invite" /></template>
<style>
.d96nfgblu {
  d: path("m3 11l9 6l9-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.melkgeemz {
  d: path("M3 11v9a1.5 1.5 0 0 0 1.5 1.5h15A1.5 1.5 0 0 0 21 20v-9");
}

.t0two85ez {
  d: path("M6.5 13.25V4A1.5 1.5 0 0 1 8 2.5h8A1.5 1.5 0 0 1 17.5 4v9.25M6.5 6h11");
}

</style>
