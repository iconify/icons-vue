<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wfnnwnbmv"/><path class="ocsxqw4ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ocsxqw4ov {
  d: path("M14.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556m-7.45 2.515C9.02 9.605 9.532 10 10 10h3a1 1 0 0 1 0 2h-3c-1.039 0-1.992-.578-2.707-1.293l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

.wfnnwnbmv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779c.52 1.556 1.603 2.735 3.003 3.551c1.093.638 2.364 1.031 3.638.985a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13");
}

</style>
