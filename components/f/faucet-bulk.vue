<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tnwd6zbqq"/><path class="sg44u1bbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:faucet-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sg44u1bbc {
  d: path("M7 2h6a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0V4H7a1 1 0 0 1 0-2M4 4v8a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0m17.764 16.168a3.004 3.004 0 0 1-4.423 1.332A3 3 0 0 1 16 19c0-.774.371-1.494.825-2.1c.436-.581.955-1.095 1.468-1.607a1 1 0 0 1 1.414 0c.513.512 1.032 1.026 1.468 1.607c.454.606.825 1.326.825 2.1c.001.401-.079.799-.236 1.168");
}

.tnwd6zbqq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5a3 3 0 0 1 3 3v3a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Zm3 14a3 3 0 1 1-6 0c0-.774.371-1.494.825-2.1c.436-.581.955-1.095 1.468-1.607a1 1 0 0 1 1.414 0c.983.982 2.292 2.233 2.293 3.707");
}

</style>
