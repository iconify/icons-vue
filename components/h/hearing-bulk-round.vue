<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u498bjggd"/><path class="bjiztub4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-bulk-round" /></template>
<style>
.bjiztub4s {
  d: path("M21.155 6.102c.297.937.448 1.915.447 2.898a9.6 9.6 0 0 1-.447 2.898a9.5 9.5 0 0 1-1.341 2.683a1 1 0 1 1-1.628-1.162a7.5 7.5 0 0 0 1.062-2.124A7.5 7.5 0 0 0 19.602 9a7.5 7.5 0 0 0-.354-2.295a7.5 7.5 0 0 0-1.062-2.124a1 1 0 0 1 .233-1.395a1 1 0 0 1 1.395.233a9.5 9.5 0 0 1 1.341 2.683M8.269 8.318c.505.283.886.752 1.079 1.296c.433 1.217-.081 2.643-1.291 3.173A2.6 2.6 0 0 1 7 13a1 1 0 0 1 0-2c.324 0 .5-.175.5-.5S7.324 10 7 10a.997.997 0 0 1-1-1a3 3 0 0 1 .236-1.168A3.004 3.004 0 0 1 10.659 6.5A3 3 0 0 1 12 9a1 1 0 0 1-2 0a.999.999 0 0 0-1.731-.682");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u498bjggd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a7 7 0 1 1 14 0c0 1.529-.372 3.012-1.326 4.23c-.71.906-1.629 1.536-2.582 2.155c-.533.347-1.147.724-1.571 1.203c-.364.411-.521.864-.521 1.412a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 2 18Z");
}

</style>
