<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2ks88bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-rear" /></template>
<style>
.c2ks88bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17v-3.5q0-1.25 1-1.75t1.41-1.68l1.18-3.39Q6.75 5.5 8 5.5h8q1.25 0 1.66 1.18l1.18 3.39q.41 1.18 1.41 1.68t1 1.75V17q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25m3.5 1.25v2.5m11.5-2.5v2.5m-3-2.5v1.25m-9.25-9h13m-8.25 5h3.5M5.25 14h2.5m8.5 0h2.5");
}

</style>
