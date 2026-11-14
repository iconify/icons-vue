<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7akqk4kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:container-cluster" /></template>
<style>
.q7akqk4kq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h4.75A1.75 1.75 0 0 1 16 4.25v2.5a1.75 1.75 0 0 1-1.75 1.75H9.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 9.5 2.5M4.25 15H9a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 9 21H4.25a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 4.25 15M15 15h4.75a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 19.75 21H15a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 15 15M10.5 4.25v2.5m2.75-2.5v2.5m-8 10v2.5M8 16.75v2.5m8-2.5v2.5m2.75-2.5v2.5M9.5 8.5l-3 6.5m7.75-6.5L17.5 15");
}

</style>
