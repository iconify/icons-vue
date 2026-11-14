<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj9re6kat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bill-overdue" /></template>
<style>
.hj9re6kat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v5.75a1.75 1.75 0 0 1-1.75 1.75H14A1.75 1.75 0 0 0 12.25 14v4.043a1.21 1.21 0 0 1-1.75 1.082l-.941-.471a1.75 1.75 0 0 0-1.607.021l-1.077.575A1.275 1.275 0 0 1 5 18.125V4.75A1.75 1.75 0 0 1 6.75 3M8.5 6.5h7m-7 3h7m2.5 5.25v3.5M18 21h.01");
}

</style>
