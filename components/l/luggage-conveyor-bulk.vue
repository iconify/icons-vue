<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnvc18blp"/><path class="smp9tlbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lnvc18blp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 8a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2ZM2 18a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

.smp9tlbnq {
  d: path("M8 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1v5a1 1 0 0 1-2 0V7a1 1 0 0 1 1-1V4h-4v2a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0V8a1 1 0 0 1-1-1Z");
}

</style>
