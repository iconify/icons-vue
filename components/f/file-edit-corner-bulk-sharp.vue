<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjexm-byy"/><path class="f3w6rac3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-edit-corner-bulk-sharp" /></template>
<style>
.bjexm-byy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.f3w6rac3a {
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1V3a1 1 0 0 1 1.698-.716l.009.008ZM16.586 8L14 5.414V8Zm-4.293 9.293l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1v-3c0-.265.105-.52.293-.707");
}

</style>
