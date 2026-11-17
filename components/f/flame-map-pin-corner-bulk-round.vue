<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qreaqh1zb"/><path class="znwteqb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-map-pin-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qreaqh1zb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 16v4.917a1 1 0 0 1-.835.986A7 7 0 0 1 9 22a6.9 6.9 0 0 1-2.725-.551a7.02 7.02 0 0 1-3.724-3.724A6.9 6.9 0 0 1 2 15c0-1.302.345-2.758 1.293-3.707A.999.999 0 0 1 5 12a1 1 0 0 0 1.387.922A.99.99 0 0 0 7 12c0-.365-.035-.737-.152-1.085c-.1-.298-.26-.579-.413-.853a17 17 0 0 1-.329-.615c-1.451-2.903-.063-5.361 2.269-7.228a1 1 0 0 1 1.606.585a8 8 0 0 0 1.281 3.004c.635.925 1.442 1.72 2.338 2.392a1 1 0 0 1 .107.093q.447.447.809.964a1.003 1.003 0 0 1-.349 1.454A6 6 0 0 0 11 16");
}

.znwteqb7e {
  d: path("M15.184 20.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m2.523-5.484a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

</style>
