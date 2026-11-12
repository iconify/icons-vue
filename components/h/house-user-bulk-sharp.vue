<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yssha6-2q"/><path class="gosf_ks8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gosf_ks8m {
  d: path("M9.236 9.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m-3.9 7.347A5 5 0 0 1 17 21a1 1 0 0 1-2 0a3 3 0 1 0-6 0a1 1 0 0 1-2 0a4.9 4.9 0 0 1 .393-1.946");
}

.yssha6-2q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.707 10.293A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0Z");
}

</style>
