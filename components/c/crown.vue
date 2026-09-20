<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wel539_fp"/><path class="qo7mzywrv"/><path clip-rule="evenodd" class="v7r822bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:crown" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qo7mzywrv {
  d: path("M11 3.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m8 2a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-16 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.v7r822bpp {
  fill-rule: evenodd;
  d: path("M4.5 16.25a1 1 0 0 1 1-1h9.251a1 1 0 1 1 0 2H5.5a1 1 0 0 1-1-1");
}

.wel539_fp {
  fill-rule: evenodd;
  d: path("m15.267 9.928l-.367.234a3 3 0 0 1-4.107-.867L10 8.105l-.793 1.19a3 3 0 0 1-4.107.867l-.367-.234L5.542 13h8.916zM3.654 6.87c-.768-.488-1.736.219-1.504 1.099l1.654 6.286A1 1 0 0 0 4.77 15h10.458a1 1 0 0 0 .967-.745l1.654-6.286c.232-.88-.736-1.587-1.504-1.099l-2.52 1.604a1 1 0 0 1-1.369-.289l-1.625-2.437a1 1 0 0 0-1.664 0L7.543 8.185a1 1 0 0 1-1.369.29z");
}

</style>
