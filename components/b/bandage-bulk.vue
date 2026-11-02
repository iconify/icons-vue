<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="avx8xbi3l"/><path class="p3ta4keoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandage-bulk" /></template>
<style>
.avx8xbi3l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p3ta4keoh {
  d: path("M6 18V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m10 0V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m-6-9h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-4 4h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2");
}

</style>
