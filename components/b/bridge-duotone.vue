<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ob3yoxb8n"/><path class="lp_rupbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bridge-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lp_rupbrq {
  d: path("M232 160h-32v-58.66a71.9 71.9 0 0 0 29 21.42a8 8 0 0 0 6-14.83A55.78 55.78 0 0 1 200 56a8 8 0 0 0-16 0a56 56 0 0 1-112 0a8 8 0 0 0-16 0a55.78 55.78 0 0 1-35 51.93a8 8 0 0 0 6 14.83a71.9 71.9 0 0 0 29-21.42V160H24a8 8 0 0 0 0 16h32v24a8 8 0 0 0 16 0v-24h112v24a8 8 0 0 0 16 0v-24h32a8 8 0 0 0 0-16m-88-33.8V160h-32v-33.8a72 72 0 0 0 32 0m-72-25a72.5 72.5 0 0 0 24 19.27V160H72Zm88 58.8v-39.52a72.5 72.5 0 0 0 24-19.27V160Z");
}

.ob3yoxb8n {
  d: path("M232 168H24v-52.65A64 64 0 0 0 64 56a64 64 0 0 0 128 0a64 64 0 0 0 40 59.35Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
