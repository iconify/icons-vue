<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gvmyg7bww"/><path class="l0cxbsbji"/><path class="rckmicclj"/><path class="n-059ea3n"/><path class="llakqobuk"/><path class="ciz9k0bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cohort-ai-outline-thin" /></template>
<style>
.ciz9k0bxi {
  d: path("M8 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gvmyg7bww {
  d: path("M2 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0cxbsbji {
  d: path("M8 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.llakqobuk {
  d: path("M11 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n-059ea3n {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rckmicclj {
  d: path("M14 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
