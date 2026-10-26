<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fneokgbtz"/><path clip-rule="evenodd" class="snqkqz2wb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-taxi-front-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fneokgbtz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.5 11.1338C21.8095 11.3124 22.0002 11.6426 22 12L22 20C22 20.5523 21.5523 21 21 21L3 21C2.4477 21 2 20.5523 2 20L2 12C1.9998 11.6426 2.1905 11.3124 2.5 11.1338L2.5 10L4.473 10L5.0083 5.8714C5.0729 5.373 5.4974 5 6 5L7.9989 5L9.5936 1.5776C9.7578 1.2253 10.1113 1 10.5 1L13.5 1C13.8887 1 14.2422 1.2253 14.4064 1.5776L16.0011 5L18 5C18.5026 5 18.9271 5.373 18.9917 5.8714L19.5269 10L21.5 10L21.5 11.1338Z");
}

.snqkqz2wb {
  fill-rule: evenodd;
  d: path("M6.3601 11L6.8787 7L17.1213 7L17.6398 11L6.3601 11ZM18 19L19 19C19.5523 19 20 19.4477 20 20L20 22C20 22.5523 19.5523 23 19 23L18 23C17.4477 23 17 22.5523 17 22L17 20C17 19.4477 17.4477 19 18 19ZM5 19L6 19C6.5523 19 7 19.4477 7 20L7 22C7 22.5523 6.5523 23 6 23L5 23C4.4477 23 4 22.5523 4 22L4 20C4 19.4477 4.4477 19 5 19ZM7.9989 5L9.5936 1.5776C9.7578 1.2253 10.1113 1 10.5 1L13.5 1C13.8887 1 14.2422 1.2253 14.4064 1.5776L16.0011 5L7.9989 5ZM6 15L9 15L9 17L6 17L6 15ZM15 15L18 15L18 17L15 17L15 15Z");
}

</style>
