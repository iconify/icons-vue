<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dzezqlb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hana-one-q" /></template>
<style>
.dzezqlb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.533 16.48l7.62-6.974v29.168m26.211-3.591L22.227 39.3V8.7l17.377 4.277V28.78m-6.665-1.84l9.528 12.08");
}

</style>
