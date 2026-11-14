<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wywkxlb-s"/><path class="zqjsjfbih"/><path class="zqdj0p5iz"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-agent" /></template>
<style>
.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wywkxlb-s {
  d: path("m3 9l1.5-5h15L21 9M3 9a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0");
}

.zqdj0p5iz {
  d: path("M12 20.9v.1H7.5v-7H12v1.1m2 2.9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.zqjsjfbih {
  d: path("M4.5 10.5V21H12m7.5-8.8v-1.7M9 4l-.5 4.5M15 4l.5 4.5");
}

</style>
