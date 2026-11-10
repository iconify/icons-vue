<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g6lliflxe"/><path class="mkegl8b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:backpack-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g6lliflxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M12 1C14.1829 1 15.9554 2.749 15.9971 4.922C15.9989 5.016 16.0668 5.096 16.1592 5.114C18.9181 5.654 21 8.083 21 11V19C21 21.209 19.2092 23 17 23H7C4.7909 23 3 21.209 3 19V11C3 8.083 5.0814 5.655 7.8398 5.114C7.9323 5.096 8.0001 5.016 8.002 4.922C8.0436 2.749 9.817 1 12 1ZM12 3C10.9 3 10 3.9 10 5H14C14 3.9 13.1 3 12 3Z");
}

.mkegl8b9y {
  d: path("M21 16H9V18C9 18.552 8.5523 19 8 19C7.4477 19 7 18.552 7 18V16H3V14H21V16ZM14 9C14.5523 9 15 9.448 15 10C15 10.552 14.5523 11 14 11H10C9.4477 11 9 10.552 9 10C9 9.448 9.4477 9 10 9H14Z");
}

</style>
