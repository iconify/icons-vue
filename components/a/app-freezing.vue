<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbvujabdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-freezing" /></template>
<style>
.vbvujabdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.997 2.5v43M45.5 24.183h-43M13.507 5.668l10.49 10.49m10.49-10.49l-10.49 10.49m-10.49 25.684l10.49-10.49m10.49 10.49l-10.49-10.49m19.227 3.321l-10.49-10.49m10.49-10.49l-10.49 10.49M5.883 34.673l10.49-10.49m-10.49-10.49l10.49 10.49");
}

</style>
