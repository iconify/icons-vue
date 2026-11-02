<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="to5613suh"/><path class="dvj5lemin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dvj5lemin {
  d: path("M7 7V3a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0v3h9V4H9v3a1 1 0 0 1-2 0m4.293 2.707a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L12.586 13H5a1 1 0 0 1 0-2h7.586Z");
}

.to5613suh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 3h11v18H8Z");
}

</style>
