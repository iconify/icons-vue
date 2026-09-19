<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_jaayc1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kerry-express" /></template>
<style>
.m_jaayc1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.22 38.9L19.126 22.218L43.5 9.17m-39-.865v31.39m0-9.666l14.687-7.856");
}

</style>
