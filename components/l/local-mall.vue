<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js6eq5mad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-mall" /></template>
<style>
.js6eq5mad {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20V8q0-.825.588-1.412T5 6h2q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6h2q.825 0 1.413.588T21 8v12q0 .825-.587 1.413T19 22zm10.538-9.462Q17 11.075 17 9h-2q0 1.25-.875 2.125T12 12t-2.125-.875T9 9H7q0 2.075 1.463 3.538T12 14t3.538-1.463M9 6h6q0-1.25-.875-2.125T12 3t-2.125.875T9 6");
}

</style>
