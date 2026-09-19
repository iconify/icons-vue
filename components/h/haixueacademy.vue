<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iplx3sbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:haixueacademy" /></template>
<style>
.iplx3sbcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.25 36.666l14.625-25.331L43.5 36.665H24L14.25 19.78L4.5 36.666z");
}

</style>
