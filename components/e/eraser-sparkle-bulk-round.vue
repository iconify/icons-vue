<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mh_ia-4dv"/><path class="n2ngjlb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mh_ia-4dv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.293 13.293l7-7a3.83 3.83 0 0 1 5.414 0l1 1a3.83 3.83 0 0 1 0 5.414l-8 8A1 1 0 0 1 11 21H7a1 1 0 0 1-.707-.293a5.243 5.243 0 0 1 0-7.414");
}

.n2ngjlb_o {
  d: path("M2.989 4.999c.134-.028.261-.107.375-.177a4.9 4.9 0 0 0 1.458-1.458c.07-.114.149-.241.177-.375L5 2.986a1 1 0 0 1 2 0l.001.003c.028.134.107.261.177.375a4.9 4.9 0 0 0 1.458 1.458c.114.07.241.149.375.177L9.014 5a1 1 0 0 1 0 2l-.003.001c-.134.028-.261.107-.375.177a4.9 4.9 0 0 0-1.458 1.458c-.07.114-.149.241-.177.375L7 9.014a1 1 0 0 1-2 0l-.001-.003c-.028-.134-.107-.261-.177-.375a4.9 4.9 0 0 0-1.458-1.458c-.114-.07-.241-.149-.375-.177L2.986 7a1 1 0 0 1 0-2Zm12.718 10.294a.999.999 0 1 1-1.414 1.414l-5-5a.999.999 0 1 1 1.414-1.414ZM11 19h10a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2");
}

</style>
