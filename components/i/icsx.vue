<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ujopkablw"/><circle class="ibpai8bgc"/><path class="fim94wi9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icsx" /></template>
<style>
.fim94wi9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 13.489V9.284m18.5 4.205V9.284m-5.114 12.664l3.432-1.868v13.727m-15.135-1.158c.948.794 1.971 1.158 4.269 1.158h.535a3.431 3.431 0 0 0 0-6.862m-4.805-5.719c.95-.791 1.974-1.152 4.271-1.146l.534.003a3.431 3.431 0 0 1 0 6.862m-2.637 0h2.637m4.789-14.962L24 14.008l-2.026-2.025M24 8.764v5.244");
}

.ibpai8bgc {
  cx: 24px;
  cy: 11.386px;
  r: 5.886px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ujopkablw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.886 11.386h7.989c.929 0 1.682.753 1.682 1.682v27.75c0 .929-.753 1.682-1.682 1.682h-27.75a1.68 1.68 0 0 1-1.682-1.682v-27.75c0-.929.753-1.682 1.682-1.682h7.989");
}

</style>
