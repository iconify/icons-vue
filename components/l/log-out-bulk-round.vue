<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ppeuxsbjl"/><path class="a8m2j0-br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-out-bulk-round" /></template>
<style>
.a8m2j0-br {
  d: path("M10 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h3c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 15 7a1 1 0 0 1-2 0a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3h3a3 3 0 0 0 3-3a1 1 0 0 1 2 0a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 10 22m7.293-12.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 .009 1.405l-.008.008l-.001.001l-3 3a1 1 0 0 1-1.414-1.414L18.586 13H11a1 1 0 0 1 0-2h7.586Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ppeuxsbjl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
