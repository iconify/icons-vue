<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fy6x5rbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fv-file-explorer" /></template>
<style>
.fy6x5rbax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.725 27.792c1.15.807 2.15 1.652 3.248 2.99c1.343-2.793 2.996-5.504 6.03-8.267m2.85 3.856a8.006 8.006 0 1 1-8.005-8.006a8.006 8.006 0 0 1 8.005 8.006M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

</style>
