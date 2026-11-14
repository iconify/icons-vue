<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw13z0b5h"/><path class="a0kcpwbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-filter" /></template>
<style>
.a0kcpwbcz {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M16.55 15h2.9a1.009 1.009 0 0 1 .8 1.625l-.939 1.221a1.5 1.5 0 0 0-.311.914v1.622A.69.69 0 0 1 18 21l-.171-.085A1.5 1.5 0 0 1 17 19.573v-.813a1.5 1.5 0 0 0-.311-.914l-.939-1.221a1.009 1.009 0 0 1 .8-1.625");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw13z0b5h {
  d: path("M3.5 3v17.5h10.8");
}

</style>
