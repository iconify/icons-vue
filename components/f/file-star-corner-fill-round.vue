<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlaiz4bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-star-corner-fill-round" /></template>
<style>
.vlaiz4bot {
  fill: currentColor;
  d: path("M4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17m9-11a2 2 0 0 0 2 2h2l-4-4Zm4.894 6.953l.966 1.931l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L17 20.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0");
}

</style>
