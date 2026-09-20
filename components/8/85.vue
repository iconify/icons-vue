<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ves40kuaa"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:85" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ves40kuaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.956 24a3.456 3.456 0 0 0 0 6.912h2.247a3.456 3.456 0 0 0 0-6.912m0 0a3.456 3.456 0 0 0 0-6.912h-2.247a3.456 3.456 0 0 0 0 6.912m0 0h2.247m6.829 5.746c.955.8 1.88 1.166 4.195 1.166h.397a3.876 3.876 0 0 0 0-7.751h-4.592v-6.073H34.5");
}

</style>
