<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tzzioqbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:backpack-thin" /></template>
<style>
.tzzioqbfu {
  fill: currentColor;
  d: path("M164 44.17V32a20 20 0 0 0-20-20h-32a20 20 0 0 0-20 20v12.17A52.05 52.05 0 0 0 44 96v120a12 12 0 0 0 12 12h144a12 12 0 0 0 12-12V96a52.05 52.05 0 0 0-48-51.83M112 20h32a12 12 0 0 1 12 12v12h-56V32a12 12 0 0 1 12-12m60 144H84v-12a12 12 0 0 1 12-12h64a12 12 0 0 1 12 12Zm-88 8h56v12a4 4 0 0 0 8 0v-12h24v48H84Zm120 44a4 4 0 0 1-4 4h-20v-68a20 20 0 0 0-20-20H96a20 20 0 0 0-20 20v68H56a4 4 0 0 1-4-4V96a44.05 44.05 0 0 1 44-44h64a44.05 44.05 0 0 1 44 44ZM148 88a4 4 0 0 1-4 4h-32a4 4 0 0 1 0-8h32a4 4 0 0 1 4 4");
}

</style>
