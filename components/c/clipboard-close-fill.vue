<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhskjgbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-close-fill" /></template>
<style>
.xhskjgbng {
  fill: currentColor;
  d: path("M16 4h1a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h1a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2M8 6H7a.997.997 0 0 0-1 1v12a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1h-1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2m2.707 5.293L12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
