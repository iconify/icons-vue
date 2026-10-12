<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmi8ozq6o"/><path class="ec0k_n4xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:butter" /></template>
<style>
.ec0k_n4xx {
  d: path("M6 11.25h10.75v5.5m0-5.5L19.5 8.5M2.75 17.75a2 2 0 0 0 2 2h14.5a2 2 0 0 0 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmi8ozq6o {
  d: path("M6 16.75v-5.5L8.75 8.5H19.5V14l-2.75 2.75Z");
}

</style>
