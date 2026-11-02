<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yssha6-2q"/><path class="p3rpenb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p3rpenb-u {
  d: path("m12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

.yssha6-2q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.707 10.293A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0Z");
}

</style>
