<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1wno8k_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dramaplay" /></template>
<style>
.d1wno8k_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.75 24H14a8.5 8.5 0 1 0 8.5 8.5V7m6.75 17H34a8.5 8.5 0 1 0-8.5-8.5V41");
}

</style>
