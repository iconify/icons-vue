<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4e0p2llr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fennec-for-lemmy" /></template>
<style>
.d4e0p2llr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.11 24a8.11 8.11 0 0 1-16.22 0a8.11 8.11 0 0 1 16.22 0m8.567 0c0 9.21-7.467 16.677-16.677 16.677S7.323 33.21 7.323 24S14.79 7.323 24 7.323S40.677 14.79 40.677 24m4.823 0c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
