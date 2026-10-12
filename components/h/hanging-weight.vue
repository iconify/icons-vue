<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="k_hcjvwmw"/><path class="z8-tfk6st"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hanging-weight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_hcjvwmw {
  cx: 12px;
  cy: 15.75px;
  r: 5.5px;
}

.z8-tfk6st {
  d: path("M12 14a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5M4.25 2.75c0 3 3.5 4.75 7.75 4.75s7.75-1.75 7.75-4.75M12 7.5V14");
}

</style>
