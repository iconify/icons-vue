<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5czi6rdr"/><path class="e_zu0lb2f"/><path class="kez9tfbhk"/><path class="bu4pt-b9w"/><path class="wlp3ibbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hostel-outline-thin" /></template>
<style>
.bu4pt-b9w {
  d: path("M13 6v3.5h5V6");
}

.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.e_zu0lb2f {
  d: path("M10 22v-5h4v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kez9tfbhk {
  d: path("M6 6v3.5h5V6");
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
