<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x14j4oble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gite-sharp" /></template>
<style>
.x14j4oble {
  fill: currentColor;
  d: path("M3 18v-7.558l3.692-3.846H8V5h1v1.596h8.308L21 10.442V18zm12-1h5v-6.136l-2.48-2.616L15 10.902zM4 17h10v-5.211H4z");
}

</style>
