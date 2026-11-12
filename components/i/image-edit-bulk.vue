<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ye6cy2b2f"/><path class="msqof81ac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.msqof81ac {
  d: path("M10 10c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 14 14h-3a1 1 0 0 1-1-1Zm-6.707 5.293a2.415 2.415 0 0 1 3.414 0l5 5a.999.999 0 1 1-1.414 1.414l-5-5a.415.415 0 0 0-.586 0l-1 1a.999.999 0 1 1-1.414-1.414Z");
}

.ye6cy2b2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
