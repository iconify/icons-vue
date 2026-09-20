<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vj-1ubcjx"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hospital-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.vj-1ubcjx {
  d: path("M4 20V7h16v13Z");
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
