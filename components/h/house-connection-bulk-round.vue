<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lo1anv21y"/><path class="ikippibij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ikippibij {
  d: path("M13 18v2h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7v-2H8.778a4 4 0 0 1-4-4V9.806c0-1.154.498-2.251 1.366-3.011l3.222-2.819a4 4 0 0 1 5.268 0l3.222 2.819a4 4 0 0 1 1.366 3.011V14a4 4 0 0 1-4 4Zm-1-2h3.222a2 2 0 0 0 2-2V9.806c0-.577-.249-1.126-.683-1.505l-3.222-2.82a2 2 0 0 0-2.634 0l-3.222 2.82a2 2 0 0 0-.683 1.505V14a2 2 0 0 0 2 2Z");
}

.lo1anv21y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.222 18H8.778a4 4 0 0 1-4-4V9.806c0-1.154.498-2.251 1.366-3.011l3.222-2.819a4 4 0 0 1 5.268 0l3.222 2.819a4 4 0 0 1 1.366 3.011V14a4 4 0 0 1-4 4");
}

</style>
