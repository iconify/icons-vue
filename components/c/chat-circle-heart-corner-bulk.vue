<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bkwnc4bwk"/><path class="a-ywxnbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-heart-corner-bulk" /></template>
<style>
.a-ywxnbfh {
  d: path("M17 14.398a3.7 3.7 0 0 1 2.375-.898c1.468 0 2.625.986 2.625 2.5c-.001 1.964-2.294 3.6-3.871 4.52q-.335.198-.682.374a1 1 0 0 1-.894 0A15.4 15.4 0 0 1 14.4 19.55c-1.103-.828-2.399-2.058-2.4-3.55c0-1.514 1.157-2.5 2.625-2.5c.869 0 1.718.335 2.375.898");
}

.bkwnc4bwk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
