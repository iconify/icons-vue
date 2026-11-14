<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p3fi3cbin"/><path class="swt8dzbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hands-helping" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p3fi3cbin {
  d: path("M12 11S8 8.75 8 6c0-1.4 1-2.5 2.25-2.5c.75 0 1.35.4 1.75 1c.4-.6 1-1 1.75-1C15 3.5 16 4.6 16 6c0 2.75-4 5-4 5m-9.5 3.5H6l3-1h4a1.5 1.5 0 0 1 0 3h-3");
}

.swt8dzbpn {
  d: path("m13.5 16.5l5-2.5a1.5 1.5 0 0 1 1.5 2.5l-6.5 4h-11");
}

</style>
