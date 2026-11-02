<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="b80t65kam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dice-bulk-round" /></template>
<style>
.b80t65kam {
  d: path("M8.01 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2ZM12 11h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m-3.99 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM16 15h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
