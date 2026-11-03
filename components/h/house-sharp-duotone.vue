<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fiz3i_bgr"/><path clip-rule="evenodd" class="o_4gopxmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fiz3i_bgr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3857 2.20711C11.7469 1.92603 12.253 1.92603 12.6142 2.20711L23 10.2891L21.7714 11.8673L21 11.2667V21.0001C20.9999 21.5523 20.5522 22.0001 20 22.0001H3.99996C3.44776 22.0001 3.00007 21.5523 2.99996 21.0001V11.2667L2.22848 11.8673L0.999962 10.2891L11.3857 2.20711Z");
}

.o_4gopxmc {
  fill-rule: evenodd;
  d: path("M9 20L9 18C9 16.3431 10.3431 15 12 15C13.6569 15 15 16.3431 15 18L15 20L9 20Z");
}

</style>
