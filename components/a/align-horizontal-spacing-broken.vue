<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvn4_6iaj"/><path class="a0ap9gbek"/><path class="a7rwy_bxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-spacing-broken" /></template>
<style>
.a0ap9gbek {
  d: path("M21 10V22M21 2V6");
}

.a7rwy_bxw {
  d: path("M8 15V16C8 17.8856 8 18.8284 8.58579 19.4142C9.17157 20 10.1144 20 12 20C13.8856 20 14.8284 20 15.4142 19.4142C16 18.8284 16 17.8856 16 16V16V8C16 6.11439 16 5.17157 15.4142 4.58579C14.8284 4 13.8856 4 12 4C10.1144 4 9.17157 4 8.58579 4.58579C8 5.17157 8 6.11438 8 8V11");
}

.fvn4_6iaj {
  d: path("M3 2V22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
