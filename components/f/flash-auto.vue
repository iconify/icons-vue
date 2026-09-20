<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3mre1dgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flash-auto" /></template>
<style>
.p3mre1dgf {
  fill: currentColor;
  d: path("M6 18.846V13H3.385V3h7.288L9 8.789h3.904zM14.567 11l3.51-9h.639l3.559 9h-.973l-1.03-2.608h-3.74L15.503 11zm2.262-3.408h3.134l-1.536-4.019h-.089z");
}

</style>
