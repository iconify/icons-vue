<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="somly9eia"/><path class="rbdthdcvo"/><path class="b969002zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-color-scale" /></template>
<style>
.b969002zr {
  d: path("M3.75 17.5V20M12 17.5V20m8.25-2.5V20m-16.5 0h16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbdthdcvo {
  fill: currentColor;
  d: path("M20.375 5za1.375 1.375 0 0 1 1.375 1.375v6.25A1.375 1.375 0 0 1 20.375 14A1.375 1.375 0 0 1 19 12.625v-6.25A1.375 1.375 0 0 1 20.375 5M8 11.75h2.75V14H8Zm5.5-2.25h2.75V14H13.5Z");
}

.somly9eia {
  d: path("M3.875 5zA1.375 1.375 0 0 1 5.25 6.375v6.25A1.375 1.375 0 0 1 3.875 14A1.375 1.375 0 0 1 2.5 12.625v-6.25A1.375 1.375 0 0 1 3.875 5m5.5 0za1.375 1.375 0 0 1 1.375 1.375v6.25A1.375 1.375 0 0 1 9.375 14A1.375 1.375 0 0 1 8 12.625v-6.25A1.375 1.375 0 0 1 9.375 5m5.5 0za1.375 1.375 0 0 1 1.375 1.375v6.25A1.375 1.375 0 0 1 14.875 14a1.375 1.375 0 0 1-1.375-1.375v-6.25A1.375 1.375 0 0 1 14.875 5");
}

</style>
