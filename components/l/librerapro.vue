<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwl6_kbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librerapro" /></template>
<style>
.kwl6_kbwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45M37.65 4.5H34v15.6l-2.92-2l-2.93 2V4.5H12.73v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95");
}

</style>
