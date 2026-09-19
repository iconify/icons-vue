<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhe964vyz"/><path class="nyjz2da7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:foxydroid" /></template>
<style>
.bhe964vyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 16.17l-9.24 5.33l-9.24 5.34V5.5l9.24 5.33zm0 0l9.24-5.34l9.24-5.33v21.34l-9.24-5.34z");
}

.nyjz2da7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.48 26.84L24 42.5V16.17l9.24 5.33zm-36.96 0l9.24-5.34L24 16.17V42.5z");
}

</style>
