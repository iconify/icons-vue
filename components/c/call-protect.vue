<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ps-0dvqzj"/><path class="w4v4akbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:call-protect" /></template>
<style>
.ps-0dvqzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.69 0 15.25-7.77 15.25-16.94v-20c-4 0-15.25-2-15.25-2s-11.26 2-15.25 2v20C8.75 35.73 22.31 43.5 24 43.5");
}

.w4v4akbwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.826 21.067c.587-.6 2.79-2.856 2.996-3.054a1.19 1.19 0 0 0 .219-1.144a23 23 0 0 1-.42-2.388a.765.765 0 0 0-.871-.67h-3.217a.57.57 0 0 0-.513.527a13.45 13.45 0 0 0 1.744 6.62l.014.025zl.002-.003a13.4 13.4 0 0 0 4.924 4.912l-.005.005l.165.092l.005.003a13.35 13.35 0 0 0 6.553 1.711a.57.57 0 0 0 .527-.513v-3.22a.765.765 0 0 0-.67-.872a23 23 0 0 1-2.386-.42a1.18 1.18 0 0 0-1.142.22c-.199.207-2.45 2.41-3.052 3");
}

</style>
