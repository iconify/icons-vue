<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uwvy5p-_w"/><path class="g8no66bjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-user-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g8no66bjq {
  d: path("M9 9a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 6a3 3 0 1 1 0 6H5a3 3 0 0 1 0-6h3.22c.236-.513.637-.935 1.104-1.246c1.513-1.009 3.839-1.009 5.352 0c.467.311.868.733 1.104 1.246ZM4.999 17A1 1 0 0 0 5 19h14a1 1 0 0 0 1-1v-.001A1 1 0 0 0 19 17Z");
}

.uwvy5p-_w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 17H5a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v8a1 1 0 0 1-1 1");
}

</style>
