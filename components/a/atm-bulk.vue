<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qsb179dft"/><path class="x3id4pbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qsb179dft {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 9h10a1 1 0 0 1 1 1v9a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-9a1 1 0 0 1 1-1");
}

.x3id4pbxh {
  d: path("M2 10V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0v-6h-3a1 1 0 0 1 0-2h3V5a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1v4h3a1 1 0 0 1 0 2H4v6a1 1 0 0 1-2 0Zm15-5a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-7.764 9.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

</style>
