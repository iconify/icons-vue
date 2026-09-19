<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="lmahcnb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:21bit" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lmahcnb1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.596 18.815l3.904-1.939l-2.512 14.248M16.18 21.596c.514-2.913 3.557-5.21 6.473-4.63c1.912.38 3.19 2.092 3.034 4.098c-.116 1.492-.848 2.964-2.038 3.869c-2.205 1.676-9.149 6.191-9.149 6.191h9.44");
}

</style>
