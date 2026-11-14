<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wyack71iq"/><path class="y04tigbvy"/><path class="fi4ocdbqc"/><path class="g0b20jb4q"/><path class="edidavbey"/><path class="w298ldjrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-gantt-broken" /></template>
<style>
.edidavbey {
  d: path("M7 13.5H14.5");
}

.fi4ocdbqc {
  d: path("M6 5.5H13");
}

.g0b20jb4q {
  d: path("M10 9.5H19.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w298ldjrg {
  d: path("M13 17.5H21.5");
}

.wyack71iq {
  d: path("M22 22H6C4.1144 22 3.1716 22 2.5858 21.4142C2 20.8284 2 19.8856 2 18V9");
}

.y04tigbvy {
  d: path("M2 5.4V2");
}

</style>
