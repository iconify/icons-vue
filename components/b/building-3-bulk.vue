<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b0ch600ub"/><path class="ws-arbcpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-bulk" /></template>
<style>
.b0ch600ub {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 21H7a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ws-arbcpt {
  d: path("M3 21a1 1 0 0 1 0-2h1v-5.039c0-.911.414-1.773 1.126-2.342l3-2.4a3 3 0 0 1 3.748 0l3 2.4A3 3 0 0 1 16 13.961V19h5a1 1 0 0 1 0 2Zm11-2v-5.039a1 1 0 0 0-.376-.78l-3-2.401a.995.995 0 0 0-1.248.001l-3.001 2.401a.99.99 0 0 0-.375.779V19Z");
}

</style>
