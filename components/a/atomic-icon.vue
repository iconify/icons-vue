<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":232};
const content = `<path class="b1b6u4blw"/><path class="bkwhjcblg"/><path class="z7frjvpwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:atomic-icon" /></template>
<style>
.b1b6u4blw {
  fill: var(--svg-color--1e6efa, #1e6efa);
  d: path("M177.68 230.745H34.967C15.655 230.745 0 215.089 0 195.778c0-19.315 15.653-34.976 34.967-34.986l80.866-.04a37.19 37.19 0 0 1 32.238 18.617z");
}

.bkwhjcblg {
  fill: var(--svg-color--ff3c5a, #ff3c5a);
  d: path("M26.491 141.083L97.848 17.489C107.504.765 128.889-4.965 145.614 4.691c16.727 9.657 22.463 31.043 12.815 47.775l-40.399 70.052a37.19 37.19 0 0 1-32.242 18.61z");
}

.z7frjvpwp {
  fill: var(--svg-color--ffc5ce, #ffc5ce);
  d: path("m179.954 54.98l71.357 123.594c9.657 16.725 3.926 38.11-12.799 47.767s-38.116 3.931-47.78-12.79l-40.47-70.012a37.19 37.19 0 0 1 .005-37.228z");
}

</style>
