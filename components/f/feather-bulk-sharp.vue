<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="npueh1f_r"/><path class="iihub62gw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:feather-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iihub62gw {
  d: path("m3.293 19.293l12-12a.999.999 0 1 1 1.414 1.414L13.414 12H17a1 1 0 0 1 0 2h-5.586l-6.707 6.707a.999.999 0 1 1-1.414-1.414");
}

.npueh1f_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.293 4.293a5.243 5.243 0 0 1 7.414 7.414l-6 6A1 1 0 0 1 13 18H7a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707Z");
}

</style>
