<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ifcreu08k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:guerrillamail" /></template>
<style>
.ifcreu08k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.8 16.2h20.8v19.5a4.39 4.39 0 0 1-3.9 3.9h-13a4.39 4.39 0 0 1-3.9-3.9Zm20.8 0h1.3V11h-5.85l-2.6-2.6h-6.5l-2.6 2.6H4.5v5.2h1.3m24.7 1.95h13m-13 7.8h11.05m-11.05 7.8h7.15");
}

</style>
