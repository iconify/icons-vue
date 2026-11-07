<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ba3iryt8e"/><path class="ioj8f-p5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-export-bulk" /></template>
<style>
.ba3iryt8e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.443 7.341L13 11.51V22a1 1 0 0 1-1.443.897l-8.443-4.17A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l8-3.951a2 2 0 0 1 1.772 0l8.557 4.226a1 1 0 0 1 0 1.793");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ioj8f-p5y {
  d: path("M11 11.51L2.717 7.42a1 1 0 0 1 .886-1.793L12 9.774l8.557-4.226A1.002 1.002 0 0 1 22 6.444V12a1 1 0 0 1-2 0V8.054l-7 3.456V22a1 1 0 0 1-2 0ZM18.586 19H15a1 1 0 0 1 0-2h3.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414Z");
}

</style>
