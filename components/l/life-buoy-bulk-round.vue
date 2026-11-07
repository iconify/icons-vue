<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kz7rx_9lb"/><path class="n23hiub1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:life-buoy-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kz7rx_9lb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.431 3.209c4.855-1.97 10.388.367 12.359 5.222a9.487 9.487 0 0 1-5.222 12.359a9.487 9.487 0 0 1-12.359-5.222c-1.97-4.855.367-10.388 5.222-12.359M9 15a4.244 4.244 0 1 0 6.002-6A4.244 4.244 0 0 0 9 15");
}

.n23hiub1s {
  d: path("m6.707 5.293l2.36 2.36a5.25 5.25 0 0 1 5.866 0l2.36-2.36a.999.999 0 1 1 1.414 1.414l-2.36 2.36a5.25 5.25 0 0 1 0 5.866l2.36 2.36a.999.999 0 1 1-1.414 1.414l-2.36-2.36a5.25 5.25 0 0 1-5.866 0l-2.36 2.36a.999.999 0 1 1-1.414-1.414l2.36-2.36a5.25 5.25 0 0 1 0-5.866l-2.36-2.36a.999.999 0 1 1 1.414-1.414m6.514 3.702a3.244 3.244 0 1 0-2.441 6.011a3.244 3.244 0 0 0 2.441-6.011");
}

</style>
