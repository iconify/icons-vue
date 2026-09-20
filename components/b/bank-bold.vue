<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="owih89nzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bank-bold" /></template>
<style>
.owih89nzy {
  fill: currentColor;
  d: path("M24 108h20v48H32a12 12 0 0 0 0 24h192a12 12 0 0 0 0-24h-12v-48h20a12 12 0 0 0 6.29-22.22l-104-64a12 12 0 0 0-12.58 0l-104 64A12 12 0 0 0 24 108m44 0h24v48H68Zm72 0v48h-24v-48Zm48 48h-24v-48h24ZM128 46.09L189.6 84H66.4ZM252 208a12 12 0 0 1-12 12H16a12 12 0 0 1 0-24h224a12 12 0 0 1 12 12");
}

</style>
