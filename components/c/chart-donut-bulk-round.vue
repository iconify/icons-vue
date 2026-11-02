<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w1he_aban"/><path class="tb3712bpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-donut-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tb3712bpl {
  d: path("M13 7.099A5.02 5.02 0 0 1 16.901 11H21a1 1 0 0 1 0 2h-4.099A5.002 5.002 0 1 1 11 7.099V3a1 1 0 0 1 2 0Zm-3.765 6.068a3.002 3.002 0 0 0 5.529-2.334a3.001 3.001 0 0 0-5.529 2.334");
}

.w1he_aban {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M12 9a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>
