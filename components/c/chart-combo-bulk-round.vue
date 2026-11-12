<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t1-bu-b9c"/><path class="ufzothbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-combo-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.t1-bu-b9c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.293 6.293c1.225-1.225 3.062-1.404 4.655-.901c.569.182 1.11.443 1.607.776c.34.229.71.408 1.1.533c.863.272 1.956.273 2.638-.408l4-4a.999.999 0 1 1 1.414 1.414l-4 4c-1.225 1.225-3.062 1.404-4.655.901a6.4 6.4 0 0 1-1.607-.776a4.3 4.3 0 0 0-1.1-.533c-.863-.272-1.956-.273-2.638.408l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

.ufzothbci {
  d: path("M4 4v12c0 1.27.804 2.405 2 2.83V16a1 1 0 0 1 2 0v3h4v-5a1 1 0 0 1 2 0v5h4v-7a1 1 0 0 1 2 0v7h1a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0");
}

</style>
