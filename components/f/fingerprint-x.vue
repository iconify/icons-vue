<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jthcnlvgu"/><path class="o28_9-bto"/><path class="um5ggrbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fingerprint-x" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jthcnlvgu {
  d: path("M6 5.75a10.2 10.2 0 0 1 12 0M5 17.25c-.15-.75-.25-1.5-.25-2.25v-1a7.25 7.25 0 0 1 14.5 0v1c0 1.5-.2 2.9-.6 4.25");
}

.o28_9-bto {
  d: path("M8.75 20.25C8.25 18.9 8 17.5 8 16v-2a4 4 0 0 1 8 0v1.5c0 1.25-.15 2.5-.5 3.5");
}

.um5ggrbnd {
  d: path("M12 14v2c0 1.75.4 3.4 1.1 4.75");
}

</style>
