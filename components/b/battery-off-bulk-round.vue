<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oa6wd4bpg"/><path class="okdait3_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oa6wd4bpg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6 6l11.285 11.285A4 4 0 0 1 15 18H6a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m12.94 8.697L10.243 6H15a4 4 0 0 1 4 4v4q0 .352-.06.697");
}

.okdait3_e {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
