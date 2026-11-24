<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b8egld_yp"/><path class="pk5s7xkzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-minus-corner-bulk-round" /></template>
<style>
.b8egld_yp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 9a3 3 0 0 0-3 3v8a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pk5s7xkzd {
  d: path("M13 15h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
