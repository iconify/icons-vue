<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-thrmbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:koleo" /></template>
<style>
.u-thrmbnt {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M16.8 43.5a5 5 0 0 1-3.536-8.535l10.931-10.932l-10.997-10.998a5 5 0 0 1 7.071-7.07l14.533 14.533a5 5 0 0 1 0 7.07L20.335 42.035a5 5 0 0 1-3.536 1.465Z");
}

</style>
