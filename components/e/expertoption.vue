<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjs9ccc1a"/><path class="tf-pf0bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expertoption" /></template>
<style>
.mjs9ccc1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.289 32.25v-16.5a4 4 0 0 0-2-3.464L26 4.036a4 4 0 0 0-4 0l-14.289 8.25a4 4 0 0 0-2 3.464v16.5a4 4 0 0 0 2 3.464L22 43.964a4 4 0 0 0 4 0l14.289-8.25a4 4 0 0 0 2-3.464");
}

.tf-pf0bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.499 20.5h4v12h-4zm7.5-2.5h4v12h-4zm7.5-2.5h4v12h-4zm7.532.976l4.344-2.508M23.999 44.064V34.032M13.139 17.73l-6.516-3.762");
}

</style>
