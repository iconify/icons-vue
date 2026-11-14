<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vz0onjxyz"/><path class="rbkrp3kdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contingency" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbkrp3kdq {
  d: path("M3.5 8V3.5H8m6 6.5l2-2m2.25-2.25L20.5 3.5m-4.5 0h4.5V8");
}

.vz0onjxyz {
  d: path("M12 21v-9L3.5 3.5");
}

</style>
