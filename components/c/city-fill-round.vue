<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umcvoqbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:city-fill-round" /></template>
<style>
.umcvoqbci {
  fill: currentColor;
  d: path("M2 11a3 3 0 0 1 3-3h3V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v7h3a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm10-5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2ZM8 20V10H5a.997.997 0 0 0-1 1v9Zm4-10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-6 2h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6.01 2H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M20 20v-5a1 1 0 0 0-1-1h-3v6ZM6 16h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m12 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
