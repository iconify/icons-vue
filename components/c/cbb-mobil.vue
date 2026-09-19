<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfvxzqbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cbb-mobil" /></template>
<style>
.xfvxzqbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5C13.783 5.5 5.5 13.783 5.5 24a18.5 18.5 0 0 0 7.447 14.775L5.5 42.5H24c10.217 0 18.5-8.283 18.5-18.5S34.217 5.5 24 5.5");
}

</style>
