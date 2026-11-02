<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v3clajbqa"/><path class="zxnb_ac5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v3clajbqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v3h1a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2v-3Z");
}

.zxnb_ac5y {
  d: path("M2 4.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 5 2h1a1 1 0 0 1 0 2H5a1 1 0 0 0-1 1v1a1 1 0 0 1-2 0ZM22 5v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3.004 3.004 0 0 1 3 3M2 19v-1a1 1 0 0 1 2 0v1c0 .268.108.525.299.713A.96.96 0 0 0 5 20h1a1 1 0 0 1 0 2H5a3.004 3.004 0 0 1-3-3m17 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0v1a3.004 3.004 0 0 1-3 3");
}

</style>
