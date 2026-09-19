<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w983fjb5a"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ds-video" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.w983fjb5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.463 9.5h14.968v13.097H16.463zm0 15.903h14.968V38.5H16.463zm18.242-7.484h3.742v3.742h-3.742zm0-7.484h3.742v3.742h-3.742zm0 15.904h3.742v3.742h-3.742zm0 7.484h3.742v3.742h-3.742zM9.553 17.919h3.742v3.742H9.553zm0-7.484h3.742v3.742H9.553zm0 15.904h3.742v3.742H9.553zm0 7.484h3.742v3.742H9.553z");
}

</style>
