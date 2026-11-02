<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="agz07tb0y"/><path class="ezls-zn4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-front-bulk-round" /></template>
<style>
.agz07tb0y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 13v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2a7 7 0 1 1 14 0m-3.316-3.381l-.004-.005a5 5 0 0 0-.226-.229l-.003-.003A5 5 0 0 0 7.101 12h9.798a4.97 4.97 0 0 0-1.215-2.381");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ezls-zn4j {
  d: path("M3 2h18a1 1 0 0 1 0 2h-8v3a1 1 0 0 1-2 0V4H3a1 1 0 0 1 0-2m4 18v-3a1 1 0 0 1 2 0v3h1a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm8 0v-3a1 1 0 0 1 2 0v3h1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
