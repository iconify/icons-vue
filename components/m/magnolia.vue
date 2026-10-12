<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qjbwkhh1m"/><path class="erwqurbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnolia" /></template>
<style>
.erwqurbdc {
  d: path("M10.25 7.25c-.25 3 .25 6 1.75 8.5m1.75-8.5c.25 3-.25 6-1.75 8.5M2.75 21l18.5-4.5M12 15.75v3m-6.5 1.58c-2.5-.58-2.75-3.58-2-6.33c2.5 1.25 3.25 3.75 2 6.33");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qjbwkhh1m {
  d: path("M12 15.75c-3.5 0-6-2.5-6-6.5c0-1.5.25-3 .75-4c1.5.25 2.75 1 3.5 2c.5-2.25 1-3.5 1.75-4.5c.75 1 1.25 2.25 1.75 4.5c.75-1 2-1.75 3.5-2c.5 1 .75 2.5.75 4c0 4-2.5 6.5-6 6.5");
}

</style>
