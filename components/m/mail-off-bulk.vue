<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="efeagdbxx"/><path class="inw1_lsym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.efeagdbxx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.923 17.68L8.243 4H19a3 3 0 0 1 3 3v10q0 .345-.077.68M4.128 4.128l15.744 15.744A3 3 0 0 1 19 20H5a3 3 0 0 1-3-3V7c0-1.32.866-2.487 2.128-2.872");
}

.inw1_lsym {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414m16.586 4l.414-.414a.999.999 0 1 1 1.414 1.414l-4.414 4.414l-.012.012l-.867.867l-1.414-1.414l.867-.867l.012-.012Z");
}

</style>
