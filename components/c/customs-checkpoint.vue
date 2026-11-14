<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rw1qb5m6u"/><path class="nuvey_b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customs-checkpoint" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nuvey_b9n {
  d: path("m8.141 10.109l8.227-4.75a1.75 1.75 0 0 1 2.39.641a1.75 1.75 0 0 1-.64 2.391l-8.227 4.75A1.75 1.75 0 0 1 7.5 12.5a1.75 1.75 0 0 1 .641-2.391m2.381-1.375l1.75 3.032m1.931-5.157l1.75 3.032M14.75 18l2 2L21 15.75");
}

.rw1qb5m6u {
  d: path("M5.25 10h.5a1.75 1.75 0 0 1 1.75 1.75v7.5A1.75 1.75 0 0 1 5.75 21h-.5a1.75 1.75 0 0 1-1.75-1.75v-7.5A1.75 1.75 0 0 1 5.25 10");
}

</style>
