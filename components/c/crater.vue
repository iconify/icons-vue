<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6m7ftbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crater" /></template>
<style>
.m6m7ftbzj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M9 5.25Q5.25 5.25 5.25 9T9 12.75T12.75 9T9 5.25M13 15q0 2.5 2.5 2.5T18 15t-2.5-2.5T13 15");
}

</style>
