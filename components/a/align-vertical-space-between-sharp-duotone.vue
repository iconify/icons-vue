<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rio-b8dic"/><path clip-rule="evenodd" class="il28pxlcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-space-between-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.il28pxlcl {
  fill-rule: evenodd;
  d: path("M1 5H23V3H1V5ZM1 21H23V19H1V21Z");
}

.rio-b8dic {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4V9C6 9.5523 6.448 10 7 10H17C17.552 10 18 9.5523 18 9V4C18 3.4477 17.552 3 17 3H7C6.448 3 6 3.4477 6 4ZM6 20V15C6 14.4477 6.448 14 7 14H17C17.552 14 18 14.4477 18 15V20C18 20.5523 17.552 21 17 21H7C6.448 21 6 20.5523 6 20Z");
}

</style>
