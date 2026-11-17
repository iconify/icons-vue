<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="p97s4jb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-shield-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

.p97s4jb1x {
  d: path("M14 11a2 2 0 0 1 2 2v1c0 1.087-.283 2.142-.969 3c-.676.844-1.629 1.417-2.584 1.894a1 1 0 0 1-.894 0C9.454 17.845 8.001 16.581 8 14v-1a2 2 0 0 1 2-2Zm-4 2v1c0 .345.035.694.14 1.023c.283.884 1.086 1.422 1.86 1.848c.774-.426 1.577-.964 1.86-1.848c.105-.329.14-.678.14-1.023v-1Z");
}

</style>
