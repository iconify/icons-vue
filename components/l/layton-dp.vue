<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uj1k8obyp"/><path class="jveojhvws"/><path class="p4yxi3n_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:layton-dp" /></template>
<style>
.jveojhvws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.276c3.717 0 7.864-.621 9.438-.881a.796.796 0 0 0 .666-.77l.543-26.347a1.063 1.063 0 0 0-.926-1.082c-1.385-.177-4.397-.455-9.72-.455s-8.336.277-9.721.455c-.542.07-.938.536-.927 1.082l.543 26.348a.796.796 0 0 0 .667.769c1.574.26 5.72.881 9.437.881");
}

.p4yxi3n_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.16 34.784c5.024.533 8.34 1.289 8.34 2.492c0 1.647-8.283 2.983-18.5 2.983S5.5 38.923 5.5 37.276c0-1.203 3.316-1.96 8.34-2.492");
}

.uj1k8obyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.16 32.888s-3.051.621-10.16.621s-10.16-.62-10.16-.62");
}

</style>
