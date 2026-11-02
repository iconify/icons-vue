<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="c2fvtcckl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:compass-bulk" /></template>
<style>
.c2fvtcckl {
  d: path("M14.928 11.629a1 1 0 0 1 0 .742l-2 5a.998.998 0 0 1-1.856 0l-2-5a1 1 0 0 1 0-.742l2-5a.998.998 0 0 1 1.856 0ZM12 9.693L11.077 12L12 14.307L12.923 12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
