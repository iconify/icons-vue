<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdfjggb_t"/><path class="yonkqpbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-night-deposit" /></template>
<style>
.hdfjggb_t {
  d: path("M9 7c0-2-1-3-1.5-4h9C16 4 15 5 15 7m4.37 5.048C18.692 10.079 17.374 8.187 15 7H9c-4 2-5 6-5 9q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37t.168.355t.202.336q.109.164.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058Q7.803 20 8 20h3.968M9.5 7h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yonkqpbaw {
  d: path("M13.75 10.25C13.5 9.5 12.9 9 12 9c-1.05 0-1.75.6-1.75 1.5c0 1.583 3.425.915 3.499 2.933m-1.243 1.512A2.3 2.3 0 0 1 12 15c-.9 0-1.55-.4-1.75-1M12 7.75V9m0 6v.9m7.5-.65a3.25 3.25 0 1 0 0 5.5a3 3 0 0 1 0-5.5Z");
}

</style>
