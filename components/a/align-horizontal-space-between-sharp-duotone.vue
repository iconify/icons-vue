<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xb0ylmb1g"/><path clip-rule="evenodd" class="y4crb2b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-between-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.xb0ylmb1g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6H9C9.552 6 10 6.4477 10 7V17C10 17.5523 9.552 18 9 18H4C3.448 18 3 17.5523 3 17V7C3 6.4477 3.448 6 4 6ZM20 6H15C14.448 6 14 6.4477 14 7V17C14 17.5523 14.448 18 15 18H20C20.552 18 21 17.5523 21 17V7C21 6.4477 20.552 6 20 6Z");
}

.y4crb2b8g {
  fill-rule: evenodd;
  d: path("M5 1V23H3V1H5ZM21 1V23H19V1H21Z");
}

</style>
