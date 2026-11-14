<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdqpd5bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fruit-bowl" /></template>
<style>
.mdqpd5bpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19c0 4.5-4.25 7.5-9.5 7.5s-9.5-3-9.5-7.5m1 0c0-3.5 2-3.75 2.75-2.75C7 9.25 9 9.5 9 13m-2.75-2.75v-2M15 13c0-3.5 2-3.75 2.75-2.75c.75-1 2.75-.75 2.75 2.75m-2.75-2.75v-2M9 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
