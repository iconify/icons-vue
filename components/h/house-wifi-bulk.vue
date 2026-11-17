<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="jihuljbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-wifi-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jihuljbmp {
  d: path("M8.86 10.292A7.3 7.3 0 0 1 12 9.597a7.3 7.3 0 0 1 3.14.695a7.3 7.3 0 0 1 2.641 2.083a1 1 0 0 1-1.562 1.25a5.3 5.3 0 0 0-1.926-1.521A5.34 5.34 0 0 0 12 11.597a5.34 5.34 0 0 0-2.293.507a5.3 5.3 0 0 0-1.926 1.521a1 1 0 0 1-1.562-1.25a7.3 7.3 0 0 1 2.641-2.083m1.7 3.16a3.82 3.82 0 0 1 4.147.841a.999.999 0 1 1-1.414 1.414A1.82 1.82 0 0 0 12 15.171a1.82 1.82 0 0 0-1.293.536a.999.999 0 1 1-1.414-1.414a3.8 3.8 0 0 1 1.267-.841M12.01 17a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

</style>
