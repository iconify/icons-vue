<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="ktgflrbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ktgflrbui {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m4 6h4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

</style>
