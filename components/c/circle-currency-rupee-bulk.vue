<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="sid01kbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-rupee-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.sid01kbop {
  d: path("M15 6a1 1 0 0 1 0 2h-.535c.181.314.318.65.409 1H15a1 1 0 0 1 0 2h-.126a4.01 4.01 0 0 1-3.479 2.981l2.312 2.312a.999.999 0 1 1-1.414 1.414l-4-4A1 1 0 0 1 9 12h2c.715 0 1.376-.38 1.733-1H9a1 1 0 0 1 0-2h3.733A2 2 0 0 0 11 8H9a1 1 0 0 1 0-2Z");
}

</style>
