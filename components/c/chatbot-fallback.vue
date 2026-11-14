<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gyoqu6sbf"/><path class="drl1_hb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-fallback" /></template>
<style>
.drl1_hb_g {
  d: path("m17 15l-1.5 1.5L17 18");
}

.gyoqu6sbf {
  d: path("M12.7 18.5H3.5V7h15v5.6M11 3v4m-3.25 5h.01m6.49 0h.01m1.24 4.5H19a2.25 2.25 0 0 1 0 4.5h-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
