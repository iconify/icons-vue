<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0yht9mit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-cloud" /></template>
<style>
.b0yht9mit {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm5 12.5q-2.5 0-2.5-2.5q0-2.261 2.044-2.477q.984-1.582 2.966-1.362q1.969.219 2.586 1.958q1.725.518 1.394 2.504q-.368 2.208-2.549 1.877z");
}

</style>
