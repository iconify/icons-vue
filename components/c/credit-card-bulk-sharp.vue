<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bc11tac6h"/><path class="ktgflrbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-bulk-sharp" /></template>
<style>
.bc11tac6h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ktgflrbui {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m4 6h4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
