<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3cwdvb-i"/><path class="p97s4jb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-shield-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o3cwdvb-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.p97s4jb1x {
  d: path("M14 11a2 2 0 0 1 2 2v1c0 1.087-.283 2.142-.969 3c-.676.844-1.629 1.417-2.584 1.894a1 1 0 0 1-.894 0C9.454 17.845 8.001 16.581 8 14v-1a2 2 0 0 1 2-2Zm-4 2v1c0 .345.035.694.14 1.023c.283.884 1.086 1.422 1.86 1.848c.774-.426 1.577-.964 1.86-1.848c.105-.329.14-.678.14-1.023v-1Z");
}

</style>
