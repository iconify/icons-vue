<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c2-ezubni"/><path class="dc7vceb_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-bulk-round" /></template>
<style>
.c2-ezubni {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 8a5 5 0 0 1 10 0v8a5 5 0 0 1-10 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dc7vceb_q {
  d: path("M17 7h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m-4 3H7a3 3 0 1 0 0 6h6a1 1 0 0 1 0 2H7A5 5 0 0 1 7 8h6a1 1 0 0 1 0 2m5 6a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0ZM6 19h3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
