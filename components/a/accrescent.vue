<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8a2tacjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:accrescent" /></template>
<style>
.e8a2tacjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.745 2.501a18.52 18.52 0 0 1 7.89 10.791c2.647 9.879-3.216 20.033-13.094 22.68a18.52 18.52 0 0 1-13.31-1.497A21.504 21.504 0 0 0 29.556 44.77c11.472-3.074 18.28-14.865 15.206-26.337A21.504 21.504 0 0 0 23.745 2.502Z");
}

</style>
