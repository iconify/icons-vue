<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r43f98s5i"/><path class="ngnirel9c"/><path class="su1_odbkd"/><path class="udbqknruk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hallucination-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngnirel9c {
  d: path("M6 9h8");
}

.r43f98s5i {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.su1_odbkd {
  d: path("m6 18 3 3");
}

.udbqknruk {
  d: path("m9 18 -3 3");
}

</style>
