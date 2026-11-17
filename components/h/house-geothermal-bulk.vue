<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zudh-bb-w"/><path class="gwb8a_2oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gwb8a_2oo {
  d: path("M13 16v2h5a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1h5v-2H8.667a3 3 0 0 1-3-3V8.574a3 3 0 0 1 1.024-2.258L10.024 3.4a3 3 0 0 1 3.952 0l3.333 2.916a3 3 0 0 1 1.024 2.258V13a3 3 0 0 1-3 3Zm-1-2h3.333a1 1 0 0 0 1-1V8.574a1 1 0 0 0-.341-.752l-3.333-2.917c-.378-.33-.94-.33-1.318 0L8.008 7.822a1 1 0 0 0-.341.752V13a.997.997 0 0 0 1 1Z");
}

.zudh-bb-w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.333 16H8.667a3 3 0 0 1-3-3V8.574a3 3 0 0 1 1.024-2.258L10.024 3.4a3 3 0 0 1 3.952 0l3.333 2.916a3 3 0 0 1 1.024 2.258V13a3 3 0 0 1-3 3");
}

</style>
