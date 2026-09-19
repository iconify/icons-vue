<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jmjhtm5ov"/><path class="fetr1u3uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bni-mobile-banking" /></template>
<style>
.fetr1u3uw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.912 29.697V18.303l7.548 11.394V18.303M18.2 24a2.848 2.848 0 1 1 0 5.697h-4.7V18.303h4.7a2.848 2.848 0 1 1 0 5.697m0 0h-4.7");
}

.jmjhtm5ov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4m25-24.197v11.394");
}

</style>
