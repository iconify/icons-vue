<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b1f_3v3sz"/><path class="uuz3y0b7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-bulk" /></template>
<style>
.b1f_3v3sz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-8a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.uuz3y0b7a {
  d: path("M13.158 7.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-5.865 4.072a2.415 2.415 0 0 1 3.414 0l1 1a.999.999 0 1 1-1.414 1.414l-1-1a.415.415 0 0 0-.586 0l-5 5a.999.999 0 1 1-1.414-1.414ZM13 18c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1Z");
}

</style>
