<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjhnzmbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-quarter-fill-sharp" /></template>
<style>
.mjhnzmbix {
  fill: currentColor;
  d: path("M12 2a9.9 9.9 0 0 1 3.827.761a9.984 9.984 0 0 1 6.05 10.803a1 1 0 0 1-1.144.832a1 1 0 0 1-.831-1.145Q20 12.63 20 12a7.9 7.9 0 0 0-.609-3.061a7.9 7.9 0 0 0-1.734-2.596a7.98 7.98 0 0 0-6.908-2.245a1 1 0 1 1-.313-1.975A10 10 0 0 1 12 2M6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122A10 10 0 0 1 6.122 3.91M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Zm-6.877 2.436a.999.999 0 1 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313a10 10 0 0 1 0-3.128m1.787 7.442a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1 1 0 1 1-1.176 1.618a10 10 0 0 1-2.212-2.212m13.968 2.212a1 1 0 1 1-1.176-1.618a8 8 0 0 0 1.77-1.77a1 1 0 1 1 1.618 1.176a10 10 0 0 1-2.212 2.212m-8.095 1.387a1 1 0 0 1 .966-1.575a8 8 0 0 0 2.502 0a1 1 0 1 1 .313 1.975a10 10 0 0 1-3.128 0a1 1 0 0 1-.653-.4");
}

</style>
