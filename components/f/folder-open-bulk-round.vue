<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gv_el1bvo"/><path class="otj5xdbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gv_el1bvo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H15a5 5 0 0 1 5 5v.281c.881.55 1.207 1.657 1.19 2.645a4.7 4.7 0 0 1-.241 1.39l-1 3C19.237 19.452 17.281 21 15 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.otj5xdbki {
  d: path("m4.051 19.684l2-6C6.764 11.547 8.721 10 11 10h8c.497 0 .959.192 1.322.529c.99.922 1.028 2.583.627 3.787l-1 3C19.237 19.452 17.281 21 15 21H5a1.002 1.002 0 0 1-.949-1.316M11 12c-1.426 0-2.609.991-3.051 2.316L6.387 19H15c1.427 0 2.609-.991 3.051-2.316l1-3c.147-.442.203-.972.054-1.421a.7.7 0 0 0-.139-.263Z");
}

</style>
