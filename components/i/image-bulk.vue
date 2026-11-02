<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ye6cy2b2f"/><path class="izu0rwddk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.izu0rwddk {
  d: path("M13.158 7.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-5.865 4.072a2.415 2.415 0 0 1 3.414 0l3 3a.415.415 0 0 0 .586 0l1-1a2.415 2.415 0 0 1 3.414 0l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.415.415 0 0 0-.586 0l-1 1a2.415 2.415 0 0 1-3.414 0l-3-3a.415.415 0 0 0-.586 0l-5 5a.999.999 0 1 1-1.414-1.414Z");
}

.ye6cy2b2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
