<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sk3hi3ben"/><path class="q2e0ojb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:light-switch-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q2e0ojb6o {
  d: path("M16 6a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm-1 5V8H9v3Zm-6 2v3h6v-3Z");
}

.sk3hi3ben {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm7 5v8h6V8Z");
}

</style>
