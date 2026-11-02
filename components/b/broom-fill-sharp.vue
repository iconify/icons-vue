<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0mo6-okb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-fill-sharp" /></template>
<style>
.k0mo6-okb {
  fill: currentColor;
  d: path("M13 3v8h3c.379 0 .725.214.894.553l4 8A1 1 0 0 1 20 21h-5v-4a1 1 0 0 0-2 0v4h-2v-4a1 1 0 0 0-2 0v4H4a1 1 0 0 1-.894-1.447l4-8A1 1 0 0 1 8 11h3V3a1 1 0 0 1 2 0");
}

</style>
