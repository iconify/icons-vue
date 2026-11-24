<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w8nr34grv"/><path class="c0zmipbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:city-bulk" /></template>
<style>
.c0zmipbxz {
  d: path("M12.01 6a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2ZM5 10a.997.997 0 0 0-1 1v9h16v-5a1 1 0 0 0-1-1h-4a1 1 0 0 1 0-2h4a3 3 0 0 1 3 3v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a3 3 0 0 1 3-3h4a1 1 0 0 1 0 2Zm7.01 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm-6 2a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm6 2a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm-6 2a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm12 0a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.w8nr34grv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 22H9a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

</style>
