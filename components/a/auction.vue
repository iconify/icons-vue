<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-a_3kbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auction" /></template>
<style>
.q-a_3kbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 38.483a2.446 2.446 0 1 1-4.891 0a2.446 2.446 0 0 1 4.891 0M9.491 30.409h20.657M6.536 7.07H23.44l10.42 33.743M15.922 7.071L5.5 40.814");
}

</style>
