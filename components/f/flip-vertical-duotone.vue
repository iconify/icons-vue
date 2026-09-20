<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sr482xb4l"/><path class="euvqoebuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flip-vertical-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.euvqoebuy {
  d: path("M56 120h160a16 16 0 0 0 6.23-30.74l-.14-.06l-159.93-64A16 16 0 0 0 40 40v64a16 16 0 0 0 16 16m0-80l.15.06L216 104H56zm160 96H56a16 16 0 0 0-16 16v64a16 16 0 0 0 22.15 14.78l159.93-64l.14-.06A16 16 0 0 0 216 136M56.15 215.93L56 216v-64h160Z");
}

.sr482xb4l {
  d: path("m219.11 159.37l-160 64A8 8 0 0 1 48 216v-64a8 8 0 0 1 8-8h160c8.71 0 11.14 12 3.11 15.37");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
