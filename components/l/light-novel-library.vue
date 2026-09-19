<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a53dw8ooe"/><path class="q4e77fbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:light-novel-library" /></template>
<style>
.a53dw8ooe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.23 4.5v15.9l2.72-3.63l2.73 3.63l-.05-15.89M12.7 4.5h-2.3c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h2.3");
}

.q4e77fbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.7 4.5v39h24.9c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2z");
}

</style>
