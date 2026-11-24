<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okjsc7yvd"/><path class="clenxebgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-search-bulk" /></template>
<style>
.clenxebgl {
  d: path("m13.708 10.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415m-3.415-.586a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.okjsc7yvd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 18H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3");
}

</style>
