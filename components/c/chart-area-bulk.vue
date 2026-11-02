<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jzfksxbjb"/><path class="yivkp20mn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jzfksxbjb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 14v-2c0-.265.105-.52.293-.707l2-2a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l4-4c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v8a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Z");
}

.yivkp20mn {
  d: path("M4 18a1 1 0 0 0 1 1h16a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V4a1 1 0 0 1 2 0Z");
}

</style>
