<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wzfuhtblc"/><path class="q8fgkhbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clarinet-sharp" /></template>
<style>
.q8fgkhbvv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01M12 13h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wzfuhtblc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6V2.75h3V6Zm.25 0H14v10.5l.38.65l1.99 3.45l.38.65h-9.5l.38-.65l1.99-3.45l.38-.65V6z");
}

</style>
