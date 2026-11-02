<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gd-4pggfu"/><path class="t7gg3sbxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hospital-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gd-4pggfu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.t7gg3sbxj {
  d: path("M13 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V7a1 1 0 0 1 2 0m8 15H3a1 1 0 0 1 0-2h6v-3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3h6a1 1 0 0 1 0 2m-8-2v-2h-2v2Z");
}

</style>
