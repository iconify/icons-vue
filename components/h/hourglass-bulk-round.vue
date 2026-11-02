<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g_7lp9baj"/><path class="a3chgg7oi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-bulk-round" /></template>
<style>
.a3chgg7oi {
  d: path("M5 2h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m0 18h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g_7lp9baj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a1 1 0 0 1 1 1v2c0 1.317-.335 2.748-1.293 3.707L13.414 12l3.293 3.293C17.665 16.252 18 17.683 18 19v2a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-2c0-1.317.335-2.748 1.293-3.707L10.586 12L7.293 8.707C6.335 7.748 6 6.317 6 5V3a1 1 0 0 1 1-1");
}

</style>
