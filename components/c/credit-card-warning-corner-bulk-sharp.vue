<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ywi0h9bjw"/><path class="yhzzkhb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-warning-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.yhzzkhb5u {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m15 10a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-.99 2a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

.ywi0h9bjw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9H10v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Z");
}

</style>
