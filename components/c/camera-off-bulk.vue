<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mmgx9_09q"/><path class="d8rmzsr4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d8rmzsr4b {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-6.261-6.261a4 4 0 0 1-5.478-5.478L1.293 3.707a.999.999 0 1 1 1.414-1.414m9.811 12.64l-2.451-2.451a2.004 2.004 0 0 0 2.451 2.451");
}

.mmgx9_09q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.923 18.68L7.914 4.672l.379-.379C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293L17.414 6H19a3 3 0 0 1 3 3v9q0 .345-.077.68m-2.051 2.192A3 3 0 0 1 19 21H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Z");
}

</style>
