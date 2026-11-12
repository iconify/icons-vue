<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f7kdimo3h"/><path class="mym23fbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-star-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f7kdimo3h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m8.86 4.884l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L7 10.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0ZM7 5.636l-.306.611a1 1 0 0 1-.753.543l-.82.117l.586.586a1 1 0 0 1 .279.871l-.077.463l.644-.321a1 1 0 0 1 .894 0l.644.321l-.077-.463a1 1 0 0 1 .279-.871l.586-.586l-.82-.117a1 1 0 0 1-.753-.543Z");
}

.mym23fbax {
  d: path("m7.894 2.953l.966 1.931l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L7 10.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0M21 6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Zm0 10H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2m-4 4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
