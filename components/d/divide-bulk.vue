<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nwzxboj1e"/><path class="ah77tub-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divide-bulk" /></template>
<style>
.ah77tub-x {
  d: path("M6 11h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.nwzxboj1e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.01 6a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm0 10a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
