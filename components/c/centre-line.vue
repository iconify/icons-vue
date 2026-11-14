<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sbwv6ubsq"/><path class="is4tjv2yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:centre-line" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is4tjv2yr {
  d: path("M2.5 8.5h3v7h-3m19-7h-3v7h3M12 12h.01");
}

.sbwv6ubsq {
  d: path("M5.125 4.5h13.75A2.625 2.625 0 0 1 21.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 16.875v-9.75A2.625 2.625 0 0 1 5.125 4.5M12 4.5v15");
}

</style>
