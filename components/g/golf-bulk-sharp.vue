<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qrv69wbkf"/><path class="j_phh1bkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_phh1bkl {
  d: path("M11 17a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm-4 2c0 .049.049.099.078.133c.144.17.344.288.541.387c1.058.529 2.591.586 3.731.344c.486-.102 1.237-.335 1.572-.731c.029-.034.078-.084.078-.133a1 1 0 0 1 2 0c0 .528-.21 1.022-.551 1.425c-1.779 2.102-7.121 2.1-8.898 0C5.21 20.021 5 19.53 5 19a1 1 0 0 1 2 0");
}

.qrv69wbkf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.447 2.106l8 4a.998.998 0 0 1 0 1.788l-7.999 4A1 1 0 0 1 9 11V3a1 1 0 0 1 1.447-.894");
}

</style>
