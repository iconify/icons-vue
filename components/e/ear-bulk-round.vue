<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gqpd50w-i"/><path class="h5mj0sb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ear-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gqpd50w-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 9a7 7 0 1 1 14 0c0 1.529-.372 3.012-1.326 4.23c-.71.906-1.629 1.536-2.582 2.155c-.533.347-1.147.724-1.571 1.203c-.364.411-.521.864-.521 1.412a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 5 18Z");
}

.h5mj0sb-j {
  d: path("M11.268 8.318c.506.283.887.752 1.08 1.296c.433 1.217-.081 2.643-1.291 3.173A2.6 2.6 0 0 1 10 13a1 1 0 0 1 0-2c.324 0 .5-.175.5-.5s-.176-.5-.5-.5a1 1 0 0 1-1-1a3.001 3.001 0 0 1 6 0a1 1 0 0 1-2 0a.999.999 0 0 0-1.732-.682");
}

</style>
