<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nby67tbva"/><path class="vkjrv4mtx"/><path class="xo754-w5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-three-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nby67tbva {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.416 10.71C4.618 14.27 8.039 17 12 17C12.98 17 14.096 16.78 14.979 16.49C14.64 20.04 11.638 23 8 23C4.134 23 1 19.87 1 16C1 13.95 2.015 11.99 3.416 10.71Z");
}

.vkjrv4mtx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C15.866 1 19 4.13 19 8C19 11.87 15.866 15 12 15C8.134 15 5 11.87 5 8C5 4.13 8.134 1 12 1Z");
}

.xo754-w5x {
  d: path("M16 9C19.866 9 23 12.13 23 16C23 19.87 19.866 23 16 23C12.134 23 9 19.87 9 16C9 12.13 12.134 9 16 9Z");
}

</style>
