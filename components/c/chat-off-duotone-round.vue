<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yi0ztsb7q"/><path class="h-mts8bah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h-mts8bah {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7c0-1.36.679-2.561 1.716-3.284M10 3h7a4 4 0 0 1 4 4v6q-.001.464-.101.899m-3 3q-.435.1-.899.101h-5M3 2l19 19");
}

.yi0ztsb7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 3h7a4 4 0 0 1 4 4v6q0 .455-.101.899Zm7 14H9c-1.05 0-2.23.232-3 1l-1 1c-.738.738-2-.524-2-2V7c0-1.313.636-2.537 1.716-3.284l13.183 13.183A4 4 0 0 1 17 17");
}

</style>
