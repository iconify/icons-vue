<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1vrjd62b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bank-solution" /></template>
<style>
.x1vrjd62b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.24 32.74L24 44.5L44.5 24L24 3.5L12.24 15.26m18.594 3.813H3.5m27.334 9.854H3.5");
}

</style>
