<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="m7kse9bsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-dizzy-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m7kse9bsz {
  d: path("m9 7.586l.293-.293a.999.999 0 1 1 1.414 1.414L10.414 9l.293.293a.999.999 0 1 1-1.414 1.414L9 10.414l-.293.293a.999.999 0 1 1-1.414-1.414L7.586 9l-.293-.293a.999.999 0 1 1 1.414-1.414ZM16.414 9l.293.293a.999.999 0 1 1-1.414 1.414L15 10.414l-.293.293a.999.999 0 1 1-1.414-1.414L13.586 9l-.293-.293a.999.999 0 1 1 1.414-1.414l.293.293l.293-.293a.999.999 0 1 1 1.414 1.414Zm-7.707 4.293a4.656 4.656 0 0 0 6.586 0a1 1 0 1 1 1.414 1.414a6.653 6.653 0 0 1-9.414 0a.999.999 0 1 1 1.414-1.414");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
