<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8r71pznw"/><path class="afj-yib6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exifthumbnailadder" /></template>
<style>
.afj-yib6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21.9h25.08v18.12h0H8.7a4.2 4.2 0 0 1-4.2-4.2z");
}

.m8r71pznw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.413 26.677l-4.39 5.61l-2.196-2.794l-4.579 5.713h5.056l6.798.037h5.73ZM8.7 7.98v4.2h0h-4.2h0v0a4.2 4.2 0 0 1 4.2-4.2m-4.2 6.96h4.2v4.2H4.5zm34.8-6.96a4.2 4.2 0 0 1 4.2 4.2v0h0h-4.2h0zm-27.84 0h4.2v4.2h-4.2zm6.96 0h4.2v4.2h-4.2zm6.96 0h4.2v4.2h-4.2zm6.96 0h4.2v4.2h-4.2zm0 27.84h4.2v4.2h-4.2zm11.16 0a4.2 4.2 0 0 1-4.2 4.2h0v-4.2zm0-20.88v4.2h-4.2v-4.2zm0 6.96v4.2h-4.2v-4.2zm0 6.96v4.2h-4.2v-4.2z");
}

</style>
