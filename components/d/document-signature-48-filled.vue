<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjf7qabrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-signature-48-filled" /></template>
<style>
.pjf7qabrr {
  fill: currentColor;
  d: path("M24 4v11.25A3.75 3.75 0 0 0 27.75 19h4.846L22.247 29.51a5 5 0 0 0-1.276 2.253l-.84 3.234a4 4 0 0 0-.097.503h-5.796a1.25 1.25 0 1 0 0 2.5h6.3c.851 1.464 2.607 2.355 4.469 1.872l3.234-.839c.85-.22 1.627-.66 2.253-1.276L40 28.397V41a3 3 0 0 1-3 3H11a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zm13.183 13.19a3.981 3.981 0 1 1 5.63 5.63L29.089 36.33c-.375.37-.842.634-1.352.767l-3.234.837c-1.476.383-2.82-.96-2.437-2.436l.838-3.234a3 3 0 0 1 .767-1.352zm.231-2.591c-.6.29-1.161.686-1.655 1.188l-.702.713H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
