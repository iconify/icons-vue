<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fc8xyi77f"/><path class="njya6jb9k"/><path class="s4m8c10_q"/><path class="d6785mbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-sankey-duotone-thin" /></template>
<style>
.d6785mbmg {
  d: path("M4 18h6l4 -4h6");
}

.fc8xyi77f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h6l4 4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njya6jb9k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h6l4 -4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s4m8c10_q {
  d: path("M4 6h6l4 4h6");
}

</style>
