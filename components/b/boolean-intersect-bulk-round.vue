<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u0fqslbus"/><path class="d1fv4o8vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d1fv4o8vo {
  d: path("M2 4.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 5 2h2a1 1 0 0 1 0 2H5a1 1 0 0 0-1 1v2a1 1 0 0 1-2 0ZM14 5v-.002A1 1 0 0 0 13 4h-2a1 1 0 0 1 0-2h2.001c.799 0 1.558.313 2.12.879c.565.564.882 1.322.879 2.121a1 1 0 0 1-2 0m8 6v2a1 1 0 0 1-2 0v-2a1 1 0 0 0-1-1a1 1 0 0 1 0-2c.799 0 1.558.311 2.121.879A2.97 2.97 0 0 1 22 11M5 16h-.002a2.996 2.996 0 0 1-2.988-2.757l-.001-.002A3 3 0 0 1 2 13v-2a1 1 0 0 1 2 0v2a.997.997 0 0 0 1 1a1 1 0 0 1 0 2m14 6h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0v2a3.004 3.004 0 0 1-3 3m-8-2h2a1 1 0 0 1 0 2h-2a2.97 2.97 0 0 1-2.121-.879A2.97 2.97 0 0 1 8 19a1 1 0 0 1 2 0a1 1 0 0 0 1 1");
}

.u0fqslbus {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 8h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3");
}

</style>
