<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5o1-bmwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freebox2" /></template>
<style>
.s5o1-bmwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.73 42.11h-9.45c-9.45 0-14.74-10.4-10-18.08l7.15-11.68c2.18-3.56 6-6.5 10.27-6.46c3.33 0 6.75 2 9.4 6.47L41 24a12.82 12.82 0 0 1 .34 11.41M24.66 5.89");
}

</style>
