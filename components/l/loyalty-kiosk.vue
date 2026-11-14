<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iv3juib-s"/><path class="uodvzgbnv"/><path class="bzj1ks4dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-kiosk" /></template>
<style>
.bzj1ks4dv {
  fill: currentColor;
  d: path("m12.441 5.643l.091.238a1.5 1.5 0 0 0 1.319.958l.254.013a.472.472 0 0 1 .273.839l-.198.16a1.5 1.5 0 0 0-.504 1.551l.066.246a.472.472 0 0 1-.713.518l-.214-.138a1.5 1.5 0 0 0-1.63 0l-.214.138a.472.472 0 0 1-.713-.518l.066-.246a1.5 1.5 0 0 0-.504-1.551l-.198-.16a.472.472 0 0 1 .273-.839l.254-.013a1.5 1.5 0 0 0 1.319-.958l.091-.238a.472.472 0 0 1 .882 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iv3juib-s {
  d: path("m6.477 3.727l9.655-1.357a2.625 2.625 0 0 1 2.964 2.234l.662 4.704a2.625 2.625 0 0 1-2.235 2.965L7.868 13.63a2.625 2.625 0 0 1-2.964-2.234l-.662-4.704a2.625 2.625 0 0 1 2.235-2.965");
}

.uodvzgbnv {
  d: path("M12 13za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 12 20a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 12 13m-5.5 8.5h11");
}

</style>
