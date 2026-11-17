<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ai237mb3y"/><path class="d_4o1x0gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-shield-bulk-sharp" /></template>
<style>
.ai237mb3y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d_4o1x0gf {
  d: path("M15 11a1 1 0 0 1 1 1v2c0 1.087-.283 2.142-.969 3c-.676.844-1.629 1.417-2.584 1.894a1 1 0 0 1-.894 0C9.454 17.845 8.001 16.581 8 14v-2a1 1 0 0 1 1-1Zm-5 2v1c0 .345.035.694.14 1.023c.283.884 1.086 1.422 1.86 1.848c.774-.426 1.577-.964 1.86-1.848c.105-.329.14-.678.14-1.023v-1Z");
}

</style>
