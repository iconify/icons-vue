<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5z10pbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:health-and-safety-sharp" /></template>
<style>
.j5z10pbvw {
  fill: currentColor;
  d: path("M10.5 15.5h3V13H16v-3h-2.5V7.5h-3V10H8v3h2.5zM12 22q-3.475-.875-5.738-3.988T4 11.1V5l8-3l8 3v6.1q0 3.8-2.262 6.913T12 22");
}

</style>
