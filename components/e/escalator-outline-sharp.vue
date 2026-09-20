<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf1dm7a1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:escalator-outline-sharp" /></template>
<style>
.cf1dm7a1n {
  fill: currentColor;
  d: path("M5.5 18h4.8l5-9h3.2V6h-4.8l-5 9H5.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
