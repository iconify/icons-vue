<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nap49abxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-health-outline" /></template>
<style>
.nap49abxs {
  fill: currentColor;
  d: path("M10.5 17h3v-2.5H16v-3h-2.5V9h-3v2.5H8v3h2.5zM4 21V9l8-6l8 6v12zm2-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
