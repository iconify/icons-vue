<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nm1tlbreh"/><path class="e03jjq99j"/><path class="emvotkb4z"/><path class="m26ojxb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-diff-outline-thin" /></template>
<style>
.e03jjq99j {
  d: path("M4 7h6");
}

.emvotkb4z {
  d: path("M4 20 20 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m26ojxb3w {
  d: path("M14 17h6");
}

.nm1tlbreh {
  d: path("M7 4v6");
}

</style>
