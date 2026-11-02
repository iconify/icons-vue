<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gvc5p2bxr"/><path class="rxju27b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magic-wand-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gvc5p2bxr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 2a1 1 0 0 1 1 1q0 1.477.087 2.06c.027.184.075.5.214.639s.455.187.639.214Q19.523 6 21 6a1 1 0 0 1 0 2q-1.477 0-2.06.087c-.184.027-.5.075-.639.214s-.187.455-.214.639Q18 9.523 18 11a1 1 0 0 1-2 0q0-1.477-.087-2.06c-.027-.184-.075-.5-.214-.639s-.455-.187-.639-.214Q14.477 8 13 8a1 1 0 0 1 0-2q1.477 0 2.06-.087c.184-.027.5-.075.639-.214s.187-.455.214-.639Q16 4.477 16 3a1 1 0 0 1 1-1M7 5h1a1 1 0 0 1 0 2H7v1a1 1 0 0 1-2 0V7H4a1 1 0 0 1 0-2h1V4a1 1 0 0 1 2 0Zm12 12h1a1 1 0 0 1 0 2h-1v1a1 1 0 0 1-2 0v-1h-1a1 1 0 0 1 0-2h1v-1a1 1 0 0 1 2 0Z");
}

.rxju27b-u {
  d: path("M12.293 10.293a.999.999 0 1 1 1.414 1.414l-10 10a.999.999 0 1 1-1.414-1.414Z");
}

</style>
