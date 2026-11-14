<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mowxoqbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:final-assembly" /></template>
<style>
.mowxoqbzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 3h9.75A2.625 2.625 0 0 1 19.5 5.625v5.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 10.875v-5.25A2.625 2.625 0 0 1 7.125 3M2.5 13.5h16.9M4.5 6.75h15M12 3v3.75M14.75 18l2 2L21 15.75");
}

</style>
