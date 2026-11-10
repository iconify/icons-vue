<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cpkxe0kzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:livelo" /></template>
<style>
.cpkxe0kzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.919 9.62l1.278 3.455a6.31 6.31 0 0 0 3.729 3.728l3.453 1.278c5.495 2.033 5.495 9.805 0 11.838l-3.453 1.278a6.31 6.31 0 0 0-3.73 3.729l-1.277 3.453c-2.033 5.495-9.805 5.495-11.838 0l-1.278-3.453a6.31 6.31 0 0 0-3.729-3.73L9.621 29.92c-5.495-2.033-5.495-9.805 0-11.838l3.453-1.278a6.31 6.31 0 0 0 3.73-3.728L18.08 9.62c2.033-5.495 9.805-5.495 11.838 0");
}

</style>
