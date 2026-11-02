<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o4z21du1e"/><path class="frzwt_t1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.frzwt_t1l {
  d: path("M13.707 9.293L15 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L16.414 12l1.293 1.293a.999.999 0 1 1-1.414 1.414L15 13.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L13.586 12l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.o4z21du1e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.293 5.293A1 1 0 0 1 9 5h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H9a1 1 0 0 1-.707-.293l-6-6a1 1 0 0 1 0-1.414Z");
}

</style>
