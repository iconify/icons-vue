<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u_8fa3j-i"/><path class="vezkfz-5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u_8fa3j-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 21H7a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1");
}

.vezkfz-5f {
  d: path("M3 19h1v-3c0-1.318.335-2.749 1.293-3.707l2-2a3.83 3.83 0 0 1 5.414 0l2 2C15.665 13.251 16 14.683 16 16v3h5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m11 0v-3c0-.751-.152-1.738-.707-2.293l-2-2a1.83 1.83 0 0 0-2.586 0l-2 2C6.153 14.262 6 15.248 6 16v3Z");
}

</style>
