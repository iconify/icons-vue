<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7njk_bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-description" /></template>
<style>
.h7njk_bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.546 3.25h.908a1.207 1.207 0 0 1 1.171 1.5l-.091.364A1.5 1.5 0 0 1 6.079 6.25h-.158a1.5 1.5 0 0 1-1.455-1.136l-.091-.364a1.207 1.207 0 0 1 1.171-1.5m.454 3za1.4 1.4 0 0 1 1.391 1.242l1.05 9.238a1.5 1.5 0 0 1-.219.964L7.25 19.25a1.474 1.474 0 0 1-2.5 0l-.972-1.556a1.5 1.5 0 0 1-.219-.964l1.05-9.238A1.4 1.4 0 0 1 6 6.25m6 1.5h8.5m-8.5 5h8.5m-8.5 5h5.5");
}

</style>
