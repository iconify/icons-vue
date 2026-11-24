<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xcbfid1eu"/><path class="smk3hfzbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.smk3hfzbw {
  d: path("M10 7h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-6 4v9h1v-1a3 3 0 1 1 6 0v1h1v-9a1 1 0 0 1 1-1h2a3.004 3.004 0 0 1 3 3v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-8.001A3 3 0 0 1 5 10h2a1 1 0 0 1 1 1m2 0h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2M4 13v7h2v-8H4.999A1 1 0 0 0 4 13m16 7v-7a1 1 0 0 0-1-1h-1v8Zm-7 0v-1a1 1 0 0 0-2 0v1Z");
}

.xcbfid1eu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 22H7a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v13a1 1 0 0 1-1 1");
}

</style>
