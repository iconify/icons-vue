<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rxnx84b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dlf-nachrichten" /></template>
<style>
.rxnx84b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.715 19.586h14.682M19.668 25.68H39.61v-2.3H19.668zm22.48 3.795v4.135H19.72v-4.135ZM16.67 22.77a9.197 9.197 0 1 1 7.002-5.803M19.715 43.5h14.682m-14.729-6.093H39.61v2.298H19.668z");
}

</style>
