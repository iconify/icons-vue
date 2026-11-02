<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r--hg2bnd"/><path class="dwxb8orqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dwxb8orqw {
  d: path("m4.707 1.293l14 14a.999.999 0 1 1-1.414 1.414l-14-14a.999.999 0 1 1 1.414-1.414");
}

.r--hg2bnd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m5 3l10 10v4c-.001 1.348-1.478 2.357-2.553 2.894c-1.057.529-2.418.28-3.095-.729A2.1 2.1 0 0 1 9 18v-5c0-.468-.395-.98-.707-1.293l-4-4a4.9 4.9 0 0 1-.928-1.26c-.47-.941-.57-2.07.221-2.861A2 2 0 0 1 5 3m11.121 6.879L9.243 3H19c.531 0 1.039.21 1.414.586c.791.791.691 1.92.221 2.861c-.235.469-.558.89-.928 1.26l-2.879 2.879Z");
}

</style>
