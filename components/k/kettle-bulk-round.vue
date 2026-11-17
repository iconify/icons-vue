<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uopt1xbiu"/><path class="uejb2_b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uejb2_b3q {
  d: path("M21 9v2a3.004 3.004 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1V9c0-.268-.108-.525-.299-.713A.96.96 0 0 0 18 8h-2a1 1 0 0 1 0-2h2a3 3 0 0 1 3 3M6 20h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.uopt1xbiu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 7v6a5 5 0 0 1-5 5h-1a5 5 0 0 1-5-5V7c0-.468-.395-.98-.707-1.293l-1-1a1.36 1.36 0 0 1-.382-1.186C4.072 2.572 5.102 2 6 2h6a5 5 0 0 1 5 5");
}

</style>
