<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ljeccnb5s"/><path class="nsfas3bbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ljeccnb5s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 11v5a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5v-5a5 5 0 0 1 4.568-4.982l1.725-1.725C9.008 3.578 9.961 3 11 3h2c1.039 0 1.992.578 2.707 1.293l1.725 1.725A5 5 0 0 1 22 11");
}

.nsfas3bbb {
  d: path("M8.315 11.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
