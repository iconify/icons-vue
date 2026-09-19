<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k05xfbwoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magic-eraser" /></template>
<style>
.k05xfbwoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.36 24.488L21.154 5.5a4.963 4.963 0 0 1 6.85-1.6l12.031 7.472a4.96 4.96 0 0 1 1.601 6.849L29.842 37.208zm20.007 12.426l-3.47 5.586a4.963 4.963 0 0 1-6.85 1.6L7.966 37.219a4.96 4.96 0 0 1-1.601-6.85l3.47-5.586");
}

</style>
