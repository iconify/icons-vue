<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="n5ktnab2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:8x3" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.n5ktnab2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 18.763c.553.463 1.15.675 2.488.675h.313a2 2 0 0 0 1.999-2h0a2 2 0 0 0-2-1.999m-2.8-3.333c.554-.461 1.15-.672 2.49-.668l.31.002a2 2 0 0 1 2 2h0a2 2 0 0 1-2 1.999m-1.536 0H14.3M33.2 32.5a2 2 0 0 0-2 2h0a2 2 0 0 0 2 2h1.3a2 2 0 0 0 2-2h0a2 2 0 0 0-2-2m0 0a2 2 0 0 0 2-2h0a2 2 0 0 0-2-2h-1.3a2 2 0 0 0-2 2h0a2 2 0 0 0 2 2m0 0h1.3");
}

</style>
