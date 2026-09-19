<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ipf6frjzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-eleven-oclock" /></template>
<style>
.ipf6frjzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 8.11V24m-.095-.022l-5.141-8.904M2.5 24c-.001 11.873 9.624 21.499 21.498 21.5s21.5-9.623 21.502-21.495V24c.001-11.873-9.624-21.499-21.498-21.5S2.502 12.123 2.5 23.996z");
}

</style>
