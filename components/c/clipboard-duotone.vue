<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xpo4ktbum"/><path clip-rule="evenodd" class="gpcgc6n6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gpcgc6n6g {
  fill-rule: evenodd;
  d: path("M6 4C6 2.3431 7.3431 1 9 1L15 1C16.6569 1 18 2.3431 18 4L18 5C18 6.6569 16.6569 8 15 8L9 8C7.3431 8 6 6.6569 6 5L6 4ZM8 4L8 5C8 5.5523 8.4477 6 9 6L15 6C15.5523 6 16 5.5523 16 5L16 4C16 3.4477 15.5523 3 15 3L9 3C8.4477 3 8 3.4477 8 4Z");
}

.xpo4ktbum {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7C3 4.7909 4.7909 3 7 3L17 3C19.2091 3 21 4.7909 21 7L21 19C21 21.2091 19.2091 23 17 23L7 23C4.7909 23 3 21.2091 3 19L3 7Z");
}

</style>
