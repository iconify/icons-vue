<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k9gdh5j2x"/><path class="eyjudf56o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-loop-right-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eyjudf56o {
  d: path("M12 17h4.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L16.586 19H12a8 8 0 1 1 8-8a1 1 0 0 1-2 0a6 6 0 0 0-2.685-5.001a6 6 0 0 0-5.65-.528A6.002 6.002 0 0 0 12 17");
}

.k9gdh5j2x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 11v7h-7a7 7 0 1 1 7-7");
}

</style>
