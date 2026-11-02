<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gd-4pggfu"/><path class="t5vn0dbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hotel-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gd-4pggfu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.t5vn0dbxu {
  d: path("M8.01 6a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-8 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2ZM9 15h6a1 1 0 0 1 0 2v3h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h6v-3a1 1 0 0 1 0-2m2 5h2v-3h-2Z");
}

</style>
