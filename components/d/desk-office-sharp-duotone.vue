<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mc7f8cb7h"/><path class="qcpbnz-xj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-office-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mc7f8cb7h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 11.0001L13.988 11.0001C13.992 11 13.996 11 14 11L21 11C21.5523 11 22 11.4477 22 12L22 22C22 22.5523 21.5523 23 21 23L14 23C13.4477 23 13 22.5523 13 22L13 13.0001L4 13.0001L4 23.0001L2 23.0001L2 12.0001C2 11.4478 2.4477 11.0001 3 11.0001L11 11.0001L11 8L13 8L13 11.0001Z");
}

.qcpbnz-xj {
  d: path("M6 8L6 2C6 1.4477 6.4477 1 7 1L17 1C17.5523 1 18 1.4477 18 2L18 8C18 8.5523 17.5523 9 17 9L7 9C6.4477 9 6 8.5523 6 8ZM13 16L22 16L22 18L13 18L13 16Z");
}

</style>
