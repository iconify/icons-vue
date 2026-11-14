<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a4z275o_q"/><path class="u7-k7vb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-roll-35mm" /></template>
<style>
.a4z275o_q {
  d: path("M3.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7-k7vb_z {
  d: path("M11 17.5h10.5v3.25H14M9.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
