<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="foauy7b8t"/><path class="ytewus2vu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.foauy7b8t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.816 5.017l16-3a1 1 0 0 1 1.167.799l.562 3a1 1 0 0 1-.798 1.167L14.322 8H21a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9c0-.313.146-.608.396-.797l-.379-2.019a1 1 0 0 1 .799-1.167");
}

.ytewus2vu {
  d: path("m2.816 5.017l10.666-2h.001l5.333-1a1 1 0 0 1 1.167.799l.562 3a1 1 0 0 1-.798 1.167l-5.333 1h-.001l-5.333 1l-5.333 1a1 1 0 0 1-1.167-.799l-.563-3a1 1 0 0 1 .799-1.167m12.212.816l3.367-.632l-.194-1.034l-3.367.632Zm-1.966.368l-.194-1.034l-3.368.632l.194 1.034Zm-8.895.598l.194 1.034l3.368-.632l-.194-1.034Zm11.347 7.344a.997.997 0 0 1 0 1.714l-5 3A.997.997 0 0 1 9 18v-6a1 1 0 0 1 1.514-.857Z");
}

</style>
