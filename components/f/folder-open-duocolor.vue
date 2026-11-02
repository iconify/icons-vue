<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c6ts44bdh"/><path class="ly0e53q2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-duocolor" /></template>
<style>
.c6ts44bdh {
  stroke-opacity: 0.4;
  d: path("M19 11V8a2 2 0 0 0-2-2h-5l-2-2H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2");
}

.ly0e53q2z {
  d: path("m5 20l2-6c.597-1.792 1.806-3 3-3h9c.984 0 1.492 1.524 1 3l-1 3c-.597 1.792-1.806 3-3 3z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
