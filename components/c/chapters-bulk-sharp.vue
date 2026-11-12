<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a39lbxsnp"/><path class="jibgq-b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chapters-bulk-sharp" /></template>
<style>
.a39lbxsnp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jibgq-b2t {
  d: path("m10.555 5.168l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 14V6a1 1 0 0 1 1.555-.832M3 20h3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m7 0h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2");
}

</style>
