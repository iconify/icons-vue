<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsb26lb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitstamp" /></template>
<style>
.fsb26lb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.467 21.32a8.41 8.41 0 0 1 0 16.818H14.59V4.5h13.876a8.41 8.41 0 0 1 0 16.82m.001-.001H14.591m0-16.819h-3.467m3.467 16.819h-3.467m3.467 16.819h-3.467m0 5.362h25.752");
}

</style>
