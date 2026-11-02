<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b0ch600ub"/><path class="e7kl5pbla"/></g>`;
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

.e7kl5pbla {
  d: path("M3 21a1 1 0 0 1 0-2h1v-4c0-1.039.577-1.991 1.293-2.707l3-3a2.414 2.414 0 0 1 3.414 0l3 3C15.422 13.008 16 13.961 16 15v4h5a1 1 0 0 1 0 2Zm11-2v-4c0-.468-.39-.976-.707-1.293l-3-3a.415.415 0 0 0-.586 0l-3 3C6.392 14.022 6 14.532 6 15v4Z");
}

</style>
