<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="clvi-7bjk"/><path class="awi9zcvet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-vertical-duotone" /></template>
<style>
.awi9zcvet {
  d: path("M2 1C2.5523 1 3 1.448 3 2V22C3 22.552 2.5523 23 2 23C1.4477 23 1 22.552 1 22V2C1 1.448 1.4477 1 2 1Z");
}

.clvi-7bjk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 13C21.6569 13 23 14.343 23 16V18C23 19.657 21.6569 21 20 21H8C6.3432 21 5 19.657 5 18V16C5 14.343 6.3432 13 8 13H20ZM12 3C13.6569 3 15 4.343 15 6V8C15 9.657 13.6569 11 12 11H8C6.3431 11 5 9.657 5 8V6C5 4.343 6.3431 3 8 3H12Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
