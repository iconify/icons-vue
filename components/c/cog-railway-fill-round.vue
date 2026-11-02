<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlky_ubij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cog-railway-fill-round" /></template>
<style>
.xlky_ubij {
  fill: currentColor;
  d: path("M5 9a3 3 0 0 1 3-3h2a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v5.382l.553-.276a1 1 0 1 1 .894 1.788l-1.105.553l.552 1.106a1 1 0 0 1-.954 1.445a1 1 0 0 1-.834-.551l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-2.211 1.105l.552 1.106a1 1 0 1 1-1.788.894l-.553-1.105l-1.106.552a1 1 0 0 1-1.445-.954a1 1 0 0 1 .551-.834L5 18.382Zm7-1h5V6a1 1 0 0 0-1-1h-3a1 1 0 0 0-1 1Zm-2 3V8H8a1 1 0 0 0-1 1v2Z");
}

</style>
