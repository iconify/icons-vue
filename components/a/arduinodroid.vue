<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izi75-bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arduinodroid" /></template>
<style>
.izi75-bwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.94 20.46a9.15 9.15 0 1 1 2 10c-3.76-4-4.25-9.41-7.72-12.92a9.14 9.14 0 1 0 0 12.92a9.2 9.2 0 0 0 2-2.9M16.07 24h-4.88m25.6 0h-4.88m2.44 2.43v-4.87");
}

</style>
