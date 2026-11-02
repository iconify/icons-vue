<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uheot-byp"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.uheot-byp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.243 3H18a1 1 0 0 1 1 1v9.757ZM5 4l14 14v2a1 1 0 0 1-1.555.832L12 17.202l-5.445 3.63A1 1 0 0 1 5 20Z");
}

</style>
