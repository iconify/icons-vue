<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b98p7nb9a"/><path class="mqn8vt71j"/><path class="o_qfmg2rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-corridor" /></template>
<style>
.b98p7nb9a {
  d: path("M7 2.5V6m10-3.5V6M6 6h12a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqn8vt71j {
  fill: currentColor;
  d: path("M6 8.5h2v2h2v2H8v2H6v-2H4v-2h2Z");
}

.o_qfmg2rf {
  d: path("M12 11.5h7M16.5 9l2.5 2.5l-2.5 2.5");
}

</style>
