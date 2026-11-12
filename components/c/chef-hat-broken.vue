<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="znosj-b8g"/><path class="w8beb4y1h"/><path class="we6kgnh-l"/><path class="cjw43km3x"/><path class="zkglr3x2x"/><path class="l5mj12bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-broken" /></template>
<style>
.cjw43km3x {
  d: path("M5 14.584C3.2341 13.8124 2 12.0503 2 10C2 7.23858 4.23858 5 7 5C7.25052 5 7.49673 5.01842 7.73736 5.05399");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5mj12bgx {
  d: path("M16.5 7V6.5C16.5 5.99416 16.4165 5.50782 16.2626 5.05399C15.6604 3.27806 13.9794 2 12 2C10.0206 2 8.33962 3.27806 7.73736 5.05399C7.58346 5.50782 7.5 5.99416 7.5 6.5V7");
}

.w8beb4y1h {
  d: path("M19 14.584L19 18C19 19.8856 19 20.8284 18.4142 21.4142C17.8284 22 16.8856 22 15 22H14");
}

.we6kgnh-l {
  stroke-linejoin: round;
  d: path("M5 18H13M17 18H19");
}

.zkglr3x2x {
  d: path("M16.2627 5.05399C16.5033 5.01842 16.7495 5 17.0001 5C19.7615 5 22.0001 7.23858 22.0001 10C22.0001 12.0503 20.766 13.8124 19.0001 14.584");
}

.znosj-b8g {
  d: path("M5 14.584V18C5 19.8856 5 20.8284 5.58579 21.4142C6.17157 22 7.11438 22 9 22H10");
}

</style>
