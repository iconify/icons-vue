<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pq9s-bbjm"/><path class="dn9_vjbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dn9_vjbnt {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L10 11.414l-6.293 6.293a.999.999 0 1 1-1.414-1.414L8.586 10L1.293 2.707a.999.999 0 1 1 1.414-1.414M14 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 14 8");
}

.pq9s-bbjm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 17.757L6.243 2H19a3 3 0 0 1 3 3ZM2.879 2.879l18.242 18.242A3 3 0 0 1 19 22H5a3 3 0 0 1-3-3V5c0-.797.314-1.558.879-2.121");
}

</style>
