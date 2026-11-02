<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lceswp0pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-code-fill" /></template>
<style>
.lceswp0pq {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm-5.707 8.707l2 2a.999.999 0 1 0 1.414-1.414L9.414 15l1.293-1.293a.999.999 0 1 0-1.414-1.414l-2 2a.997.997 0 0 0 0 1.414m7.414-3.414a.999.999 0 1 0-1.414 1.414L14.586 15l-1.293 1.293a.999.999 0 1 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414Z");
}

</style>
