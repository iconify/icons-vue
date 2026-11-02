<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kxtpr87yv"/><path class="g_0sa-bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g_0sa-bqq {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-6.35-6.349c-.57.399-1.242.642-1.943.642a4 4 0 0 1-4-4c0-.701.243-1.373.642-1.943l-7.349-7.35a.999.999 0 1 1 1.414-1.414m9.776 12.604l-2.38-2.38A1.2 1.2 0 0 0 10 13a2 2 0 0 0 2 2c.166 0 .33-.037.483-.103");
}

.kxtpr87yv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.475 18.233L7.914 4.672l.379-.379C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293l1.725 1.725A5 5 0 0 1 22 11v5a5 5 0 0 1-.525 2.233m-2.083 2.159c-.734.4-1.556.608-2.392.608H7a5 5 0 0 1-5-5v-5a5.01 5.01 0 0 1 3.297-4.703Z");
}

</style>
