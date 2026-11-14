<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="invwhvbuu"/><path class="mzs0erbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fruit-cage" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.invwhvbuu {
  d: path("M2.5 20.5v-8a9.5 9 0 0 1 19 0v8Zm0-8h19");
}

.mzs0erbaj {
  d: path("M12 3.5v9m-4.75 0c0-5 2.25-8 4.75-9m4.75 9c0-5-2.25-8-4.75-9m-6 17c-1.5 0-1.5-3 .75-3C7 15.25 10.5 14.75 12 16.25c1.5-1.5 5-1 5.25 1.25c2.25 0 2.25 3 .75 3m-8-2.25h.01m3.99 0h.01");
}

</style>
