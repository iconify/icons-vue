<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gnonnijbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auction" /></template>
<style>
.gnonnijbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 38.483a2.446 2.446 0 0 1-2.446 2.446h0a2.446 2.446 0 1 1 2.446-2.446M9.491 30.409h20.657M6.536 7.07H23.44l10.42 33.743M15.922 7.071L5.5 40.814");
}

</style>
