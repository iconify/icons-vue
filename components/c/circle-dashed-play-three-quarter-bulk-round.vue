<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vzttly6bv"/><path class="ecvddfhlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-three-quarter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ecvddfhlw {
  d: path("M4 11.94A7.997 7.997 0 0 0 11.998 20H12a8.001 8.001 0 0 0 5.657-13.657a7.99 7.99 0 0 0-6.908-2.244a1 1 0 0 1-.313-1.976a10 10 0 0 1 11.542 9.215a10 10 0 0 1-8.656 10.576A10.004 10.004 0 0 1 2.123 10.436a1 1 0 0 1 1.976.313A8 8 0 0 0 4 11.94m3.616-7.645v.001a1 1 0 0 1-.318 1.232a8 8 0 0 0-1.77 1.77A1 1 0 0 1 3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 0 1 1.494.385M9 10c0-.428.121-.845.355-1.204c.699-1.07 2.146-1.33 3.2-.628l3 2a2.202 2.202 0 0 1 0 3.664l-3 2c-1.054.702-2.501.442-3.2-.628A2.2 2.2 0 0 1 9 14Zm2 4c0 .087.05.155.127.193c.106.053.22.04.318-.025l3-2a.203.203 0 0 0 0-.336l-3-2a.31.31 0 0 0-.318-.025A.21.21 0 0 0 11 10Z");
}

.vzttly6bv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.555 8.168l3 2a2.202 2.202 0 0 1 0 3.664l-3 2c-1.054.702-2.501.442-3.2-.628A2.2 2.2 0 0 1 9 14v-4c0-.428.121-.845.355-1.204c.699-1.07 2.146-1.33 3.2-.628");
}

</style>
