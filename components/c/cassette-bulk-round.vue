<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="nv6w0uu-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cassette-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

.nv6w0uu-u {
  d: path("M5.236 8.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m8 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-5.943 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m8 0a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m-7.187 3.846A1 1 0 0 1 9 14h6c.379 0 .725.214.894.553l2 4a1 1 0 1 1-1.788.894L14.382 16H9.618l-1.724 3.447a1 1 0 1 1-1.788-.894Z");
}

</style>
