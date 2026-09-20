<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py6bq6b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-legroom-reduced-outline-sharp" /></template>
<style>
.py6bq6b5d {
  fill: currentColor;
  d: path("M14 21v-3l1-4H6V3h6v6h6.25l.95 1.275L17 18h3v3zm-2-4H3V3h2v12h7z");
}

</style>
