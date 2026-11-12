<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy0vxkbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-share-corner-fill-sharp" /></template>
<style>
.uy0vxkbax {
  fill: currentColor;
  d: path("M3 3h7c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m18 15a1 1 0 0 1-2 0v-1.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L17.586 15H16a1 1 0 0 1 0-2h4a.997.997 0 0 1 1 1Z");
}

</style>
