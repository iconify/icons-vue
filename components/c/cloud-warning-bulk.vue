<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qq7y_sbgc"/><path class="rsywueblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-warning-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qq7y_sbgc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 20a6 6 0 0 1-.74-11.955C6.794 6.596 7.715 5.283 9 4.408a6.17 6.17 0 0 1 4.398-1.022a6 6 0 0 1 2.151.755c2.147 1.246 3.217 3.547 3.415 5.951A5.002 5.002 0 0 1 18 20Z");
}

.rsywueblk {
  d: path("M13 13a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
