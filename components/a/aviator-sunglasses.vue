<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r37_zuhti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aviator-sunglasses" /></template>
<style>
.r37_zuhti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h7.25c.25 3.5-.75 6.75-3.25 6.75S2.75 13 3 9m18 0h-7.25c-.25 3.5.75 6.75 3.25 6.75S21.25 13 21 9M10.25 9h3.5m-9 3.5L7 10.25m12.25 2.25L17 10.25");
}

</style>
