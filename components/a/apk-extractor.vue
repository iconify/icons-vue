<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6gg2vb7n"/><path class="gpli-3qxk"/><path class="pnzimus3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apk-extractor" /></template>
<style>
.gpli-3qxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.314 32.221a1.613 1.613 0 1 1 1.614-1.613a1.613 1.613 0 0 1-1.614 1.613m9.39 0a1.613 1.613 0 1 1 1.613-1.613a1.613 1.613 0 0 1-1.613 1.613");
}

.o6gg2vb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 14.5h37v27h-37zm0 0l5-8h27l5 8M24 6.5v12");
}

.pnzimus3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.289a11.5 11.5 0 0 1 11.5 11.5v1.641h0h-23h0v-1.641a11.5 11.5 0 0 1 11.5-11.5m-9.931-1.719l3.268 3.845m16.594-3.845l-3.268 3.845");
}

</style>
