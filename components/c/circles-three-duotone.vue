<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zx8fswbeq"/><path class="vkjrv4mtx"/><path class="xo754-w5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-three-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vkjrv4mtx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C15.866 1 19 4.13 19 8C19 11.87 15.866 15 12 15C8.134 15 5 11.87 5 8C5 4.13 8.134 1 12 1Z");
}

.xo754-w5x {
  d: path("M16 9C19.866 9 23 12.13 23 16C23 19.87 19.866 23 16 23C12.134 23 9 19.87 9 16C9 12.13 12.134 9 16 9Z");
}

.zx8fswbeq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.3818 11.83C2.5963 11.54 2.9169 11.45 3.2256 11.52C3.5337 11.58 3.8312 11.8 3.9961 12.12C5.4906 15.02 8.5134 17 12 17C12.5257 17 13.0412 16.95 13.542 16.87C13.8883 16.81 14.2332 16.91 14.4658 17.11C14.6695 17.29 14.7778 17.61 14.7384 17.89C13.8926 20.81 11.1872 23 8 23C4.134 23 1 19.87 1 16C1 14.44 1.514 12.99 2.3818 11.83Z");
}

</style>
