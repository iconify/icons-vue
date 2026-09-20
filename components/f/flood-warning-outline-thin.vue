<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uweslxo3x"/><path class="mdaiofb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flood-warning-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdaiofb_w {
  d: path("M7 15.5 9.5 13l2.5 2.5 2.5 -2.5 2.5 2.5");
}

.uweslxo3x {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>
