<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r0_jamkji"/><path class="dn9_vjbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dn9_vjbnt {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L10 11.414l-6.293 6.293a.999.999 0 1 1-1.414-1.414L8.586 10L1.293 2.707a.999.999 0 1 1 1.414-1.414M14 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 14 8");
}

.r0_jamkji {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.951 17.708L6.292 2.049Q6.644 1.999 7 2h10a5 5 0 0 1 5 5v10q0 .356-.049.708M3.464 3.464l17.072 17.072A4.98 4.98 0 0 1 17 22H7a5 5 0 0 1-5-5V7c0-1.33.522-2.597 1.464-3.536");
}

</style>
