<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fokqn0b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:island" /></template>
<style>
.fokqn0b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.16 34.53H4.5l11.83-15l3.28 4.15l7.81-10.24L43.5 34.53Zm0 0l-8.55-10.82");
}

</style>
