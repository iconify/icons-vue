<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bg2q8aben"/><path class="wa4p37bqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-export-bulk-round" /></template>
<style>
.bg2q8aben {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.443 7.341L13 11.51V22a1 1 0 0 1-1.443.897l-7.885-3.894A3 3 0 0 1 2 16.313V7.687c0-1.141.648-2.184 1.672-2.69l7-3.456a3 3 0 0 1 2.656 0l8.115 4.007a1 1 0 0 1 0 1.793");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wa4p37bqp {
  d: path("M11 11.51L2.877 7.499a1 1 0 0 1 .886-1.793L12 9.774l8.557-4.226A1.002 1.002 0 0 1 22 6.444V12a1 1 0 0 1-2 0V8.054l-7 3.456V22a1 1 0 0 1-2 0ZM18.586 19H15a1 1 0 0 1 0-2h3.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414Z");
}

</style>
