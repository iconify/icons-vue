<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f-o-g9hiq"/><path class="tkalyqbxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:google-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f-o-g9hiq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.944 10a1 1 0 0 1 .994.889Q22 11.442 22 12a10 10 0 0 1-8.017 9.801a9.996 9.996 0 0 1-11.197-5.908a10.03 10.03 0 0 1 0-7.786A9.99 9.99 0 0 1 12 2a9.9 9.9 0 0 1 3.336.573a9.9 9.9 0 0 1 2.954 1.653a1 1 0 0 1 .04 1.52l-2.655 2.392a1 1 0 0 1-1.216.094A4.5 4.5 0 1 0 15.354 15H13a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Z");
}

.tkalyqbxr {
  d: path("M13 10h7.944a1 1 0 0 1 .994.889a10 10 0 0 1-.188 3.333a1 1 0 0 1-.975.778H13a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1");
}

</style>
