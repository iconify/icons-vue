<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_5qrnm1b"/><path class="s50v3zbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autodoc-ru" /></template>
<style>
.s50v3zbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.041 35.695l-3.27-3.288a17.03 17.03 0 0 0-.005-16.82l3.273-3.282a21.15 21.15 0 0 0-6.385-6.346l-3.258 3.264a17 17 0 0 0-16.806.002l-3.286-3.259a21.4 21.4 0 0 0-6.364 6.37l3.271 3.273a16.98 16.98 0 0 0 .001 16.786L5.94 35.673a21.5 21.5 0 0 0 6.364 6.37l3.286-3.26a17 17 0 0 0 16.806.002l3.258 3.261a21.2 21.2 0 0 0 6.387-6.35Z");
}

.w_5qrnm1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.5 18.501l-.006-15.266a21.3 21.3 0 0 1 11.013-.014L29.5 18.5l15.281-.001a21.3 21.3 0 0 1-.014 11.002L29.5 29.5l.006 15.266a21.1 21.1 0 0 1-11.013 0L18.5 29.5l-15.266.006a21.1 21.1 0 0 1 0-11.013z");
}

</style>
