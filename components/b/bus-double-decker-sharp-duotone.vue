<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c9-s46bhz"/><path class="mmmml0bfy"/><path class="rmxoar1zj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-double-decker-sharp-duotone" /></template>
<style>
.c9-s46bhz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 13L1 13L1 11L3 11L3 2C3 1.4477 3.4477 1 4 1L20 1C20.5523 1 21 1.4477 21 2L21 11L23 11L23 13Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mmmml0bfy {
  d: path("M5 7L11 7L11 11L5 11ZM13 7L19 7L19 11L13 11ZM6 19L8 19C8.5523 19 9 19.4477 9 20L9 22C9 22.5523 8.5523 23 8 23L4 23C3.4477 23 3 22.5523 3 22L3 20C3 19.4477 3.4477 19 4 19ZM18 19L20 19C20.5523 19 21 19.4477 21 20L21 22C21 22.5523 20.5523 23 20 23L16 23C15.4477 23 15 22.5523 15 22L15 20C15 19.4477 15.4477 19 16 19Z");
}

.rmxoar1zj {
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16ZM17 16C17 16.5523 16.5523 17 16 17C15.4477 17 15 16.5523 15 16C15 15.4477 15.4477 15 16 15C16.5523 15 17 15.4477 17 16Z");
}

</style>
