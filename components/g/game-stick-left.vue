<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpq1fo53z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-stick-left" /></template>
<style>
.gpq1fo53z {
  fill: currentColor;
  d: path("M17 15.35V18q0 .825-.587 1.413T15 20H9q-.825 0-1.412-.587T7 18v-2.65q-2.275-.8-3.637-2.187T2 10.075q0-2.525 2.913-4.3T12 4t7.088 1.775t2.912 4.3q0 1.7-1.362 3.088T17 15.35m-6.225-2.85H14v-.9h-2.225V7.5h-1z");
}

</style>
