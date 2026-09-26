<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o39p3yavl"/><path clip-rule="evenodd" class="e4dn-ob3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-double-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4dn-ob3i {
  fill-rule: evenodd;
  d: path("M1 20L1 11C1 10.4477 1.4477 10 2 10L22 10C22.5523 10 23 10.4477 23 11L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20ZM3 12L3 14L11 14L11 12L3 12ZM13 12L13 14L21 14L21 12L13 12Z");
}

.o39p3yavl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 20L1 11C1 10.4477 1.4477 10 2 10L4 10L4 4C4 3.4477 4.4477 3 5 3L19 3C19.5523 3 20 3.4477 20 4L20 10L22 10C22.5523 10 23 10.4477 23 11L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20Z");
}

</style>
