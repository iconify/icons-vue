<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t-euypbap"/><path class="kpspt_bpo"/><path class="yo-0d--rc"/><path class="jnysnpbhj"/><path class="uto0n9pso"/><path class="fs--blxyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-pair-outline-thin" /></template>
<style>
.fs--blxyx {
  d: path("M9 13v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnysnpbhj {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.t-euypbap {
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.uto0n9pso {
  d: path("M7 16h10");
}

.yo-0d--rc {
  d: path("M15 8v3");
}

</style>
