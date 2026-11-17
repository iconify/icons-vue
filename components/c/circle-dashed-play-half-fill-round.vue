<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1bf9acdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-half-fill-round" /></template>
<style>
.i1bf9acdf {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10a10 10 0 0 1-1.564-.123a1 1 0 1 1 .313-1.975a7.999 7.999 0 0 0 6.444-13.987a7.99 7.99 0 0 0-6.444-1.817a1 1 0 1 1-.313-1.975A10 10 0 0 1 12 2M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91M9 10c0-.428.121-.845.355-1.204c.699-1.07 2.146-1.33 3.2-.628l3 2a2.202 2.202 0 0 1 0 3.664l-3 2c-1.054.702-2.501.442-3.2-.628A2.2 2.2 0 0 1 9 14Zm-6.877.436a.999.999 0 1 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313a10 10 0 0 1 0-3.128m1.787 7.442a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1 1 0 1 1-1.176 1.618a10 10 0 0 1-2.212-2.212");
}

</style>
