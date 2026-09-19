<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8-tqbbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edpzero" /></template>
<style>
.s8-tqbbix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.34 36.27A21.51 21.51 0 0 1 36.27 6.34m5.39 5.39a21.51 21.51 0 0 1-29.93 29.93");
}

</style>
