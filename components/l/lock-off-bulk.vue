<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qd97vzbyw"/><path class="hj0t4uosh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hj0t4uosh {
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-19-19a.999.999 0 1 1 1.414-1.414m5.757 2.585a1 1 0 0 1 0-1.414a5.003 5.003 0 0 1 7.072 0A4.98 4.98 0 0 1 17 7v2a1 1 0 0 1-2 0V7a3 3 0 0 0-5.12-2.121a1 1 0 0 1-1.415.001Z");
}

.qd97vzbyw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m18.707 19.707l1.414 1.414A3 3 0 0 1 18 22H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h1ZM21 17.757L11.243 8H18a3 3 0 0 1 3 3Z");
}

</style>
