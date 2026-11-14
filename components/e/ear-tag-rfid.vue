<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eaqt-bcpn"/><path class="fmi4n1-_f"/><path class="gdt87wv9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ear-tag-rfid" /></template>
<style>
.eaqt-bcpn {
  d: path("M2.5 10a4.5 4.5 0 0 1 9 0v9A2.5 2.5 0 0 1 9 21.5H5A2.5 2.5 0 0 1 2.5 19Z");
}

.fmi4n1-_f {
  d: path("M5.5 10.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.621-2.871a3 3 0 0 1 0 4.242m1.945-6.187a5.75 5.75 0 0 1 0 8.132");
}

.gdt87wv9h {
  d: path("M18.01 3.49a8.5 8.5 0 0 1 0 12.02");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
