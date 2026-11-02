<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n1ptp7-kw"/><path class="j_phh1bkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_phh1bkl {
  d: path("M11 17a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm-4 2c0 .049.049.099.078.133c.144.17.344.288.541.387c1.058.529 2.591.586 3.731.344c.486-.102 1.237-.335 1.572-.731c.029-.034.078-.084.078-.133a1 1 0 0 1 2 0c0 .528-.21 1.022-.551 1.425c-1.779 2.102-7.121 2.1-8.898 0C5.21 20.021 5 19.53 5 19a1 1 0 0 1 2 0");
}

.n1ptp7-kw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7c0-.633.184-1.247.536-1.774a3.44 3.44 0 0 1 1.328-1.154c1.126-.563 2.463-.526 3.583.034A3.21 3.21 0 0 1 16.236 7a3.21 3.21 0 0 1-1.789 2.894l-3.999 2A1 1 0 0 1 9 11Z");
}

</style>
