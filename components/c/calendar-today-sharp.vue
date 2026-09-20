<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n11_vlpzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-today-sharp" /></template>
<style>
.n11_vlpzq {
  fill: currentColor;
  d: path("M3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
