<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z26jhbbft"/><path class="z8g2jgblp"/><path class="jyz8nlkxs"/><path class="dpjt_8byn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beaker-outline-thin" /></template>
<style>
.dpjt_8byn {
  d: path("M17 5h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyz8nlkxs {
  d: path("M3 5h4");
}

.z26jhbbft {
  d: path("M5 5v15h14V5");
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
