<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y-fbgub1s"/><path class="hj0t4uosh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hj0t4uosh {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-19-19a.999.999 0 1 1 1.414-1.414m5.757 2.585a1 1 0 0 1 0-1.414a5.003 5.003 0 0 1 7.072 0A4.98 4.98 0 0 1 17 7v2a1 1 0 0 1-2 0V7a3 3 0 0 0-5.12-2.121a1 1 0 0 1-1.415.001Z");
}

.y-fbgub1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.951 17.708L11.243 8H16a5 5 0 0 1 5 5v4q0 .356-.049.708m-2.83 1.413l1.415 1.415A4.98 4.98 0 0 1 16 22H8a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4.083-4.917Z");
}

</style>
