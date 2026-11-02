<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="c4p-m2ldo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-bulk-round" /></template>
<style>
.c4p-m2ldo {
  d: path("M5 12c1.317 0 2.748.335 3.707 1.293l1 1c.948.948 3.638.948 4.586 0l1-1C16.252 12.335 17.683 12 19 12h2a1 1 0 0 1 0 2h-2c-.748 0-1.737.152-2.293.707l-1 1C14.748 16.665 13.317 17 12 17s-2.748-.335-3.707-1.293l-1-1C6.737 14.152 5.748 14 5 14H3a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l3h0twbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

</style>
