<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn3_4f06n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-check-corner-fill" /></template>
<style>
.dn3_4f06n {
  fill: currentColor;
  d: path("M16 4h1a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V7a1 1 0 0 0-1-1h-1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2H7a.997.997 0 0 0-1 1v12a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h1a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2m-2.293 12.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414");
}

</style>
