<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jje0epbum"/><path class="kfdmhd64i"/><path class="e4btx4zel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flaky-test-outline-thin" /></template>
<style>
.e4btx4zel {
  d: path("m21 15 -6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jje0epbum {
  d: path("m3 7 3 3 5 -5");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

</style>
