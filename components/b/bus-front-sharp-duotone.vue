<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m3vbcrb2k"/><path clip-rule="evenodd" class="ntgi2vl5b"/><path clip-rule="evenodd" class="ck1iowbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-front-sharp-duotone" /></template>
<style>
.ck1iowbek {
  fill-rule: evenodd;
  d: path("M9 14C9 14.5523 8.5523 15 8 15C7.4477 15 7 14.5523 7 14C7 13.4477 7.4477 13 8 13C8.5523 13 9 13.4477 9 14ZM17 14C17 14.5523 16.5523 15 16 15C15.4477 15 15 14.5523 15 14C15 13.4477 15.4477 13 16 13C16.5523 13 17 13.4477 17 14Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.m3vbcrb2k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7.0001L3 3C3 2.4477 3.4477 2 4 2L20 2C20.5523 2 21 2.4477 21 3L21 7.0001L23 7.0001L23 9.0001L21 9.0001L21 10.0001C21 10.0027 21 10.0053 21 10.0079L21 18C21 18.5523 20.5523 19 20 19L4 19C3.4477 19 3 18.5523 3 18L3 9.0001L1 9.0001L1 7.0001L3 7.0001Z");
}

.ntgi2vl5b {
  fill-rule: evenodd;
  d: path("M13 4L19 4L19 9L13 9L13 4ZM11 9L5 9L5 4L11 4L11 9ZM16 17L20 17C20.5523 17 21 17.4477 21 18L21 21C21 21.5523 20.5523 22 20 22L16 22C15.4477 22 15 21.5523 15 21L15 18C15 17.4477 15.4477 17 16 17ZM4 17L8 17C8.5523 17 9 17.4477 9 18L9 21C9 21.5523 8.5523 22 8 22L4 22C3.4477 22 3 21.5523 3 21L3 18C3 17.4477 3.4477 17 4 17Z");
}

</style>
