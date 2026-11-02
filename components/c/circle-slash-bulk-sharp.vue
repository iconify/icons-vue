<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="s2kkkfbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-slash-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.s2kkkfbfu {
  d: path("M18.707 17.293a.999.999 0 1 1-1.414 1.414l-12-12a.999.999 0 1 1 1.414-1.414Z");
}

</style>
