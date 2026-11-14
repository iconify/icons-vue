<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_4qg_lys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lymph-node" /></template>
<style>
.v_4qg_lys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 7C10.75 7 9 9.25 9 12s1.75 5 4.5 5c1.5 0 2.5-.75 2.25-2.25c-.25-1-1.5-1.5-1.5-2.75s1.25-1.75 1.5-2.75C16 7.75 15 7 13.5 7m-1-4.5V7m0 10v4.5m1.75-9.5h7.25");
}

</style>
