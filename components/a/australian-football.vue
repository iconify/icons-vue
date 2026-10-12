<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqboe6byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:australian-football" /></template>
<style>
.eqboe6byv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25V14.5m5.25 6.75v-10.5m6.5 10.5v-10.5m5.25 10.5V14.5M7.75 5.75a4.25 3 0 1 0 8.5 0a4.25 3 0 1 0-8.5 0m2.75 0h3");
}

</style>
