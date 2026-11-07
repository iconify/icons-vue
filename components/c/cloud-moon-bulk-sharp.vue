<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pd583sppo"/><path class="ysxtksbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pd583sppo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.667 22a3.668 3.668 0 0 1-.7-7.267a4.7 4.7 0 0 1 1.913-2.071a4.84 4.84 0 0 1 3.102-.568c2.138.322 3.657 1.935 3.959 4.057A3 3 0 0 1 13 22Z");
}

.ysxtksbaj {
  d: path("M20.998 8H21a1 1 0 0 1 1 .993V9a6.99 6.99 0 0 1-4.492 6.535a1.001 1.001 0 0 1-.716-1.868a5 5 0 0 0 2.651-2.373a5.269 5.269 0 0 1-6.736-6.739A4.99 4.99 0 0 0 10 9a1 1 0 0 1-2 0a6.9 6.9 0 0 1 .55-2.725a7 7 0 0 1 1.5-2.225A6.97 6.97 0 0 1 15 2a1 1 0 0 1 .625 1.781a3.269 3.269 0 1 0 4.594 4.594c.189-.236.476-.374.779-.375");
}

</style>
