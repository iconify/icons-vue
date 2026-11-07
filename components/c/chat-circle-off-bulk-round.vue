<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u-iinsjhp"/><path class="em57w9skn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em57w9skn {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

.u-iinsjhp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.919 4.677L7.417 3.175a9.945 9.945 0 0 1 13.408 13.408Zm-3.951.291l14.064 14.064a9.93 9.93 0 0 1-11.163 2.014l-4.673.935a1 1 0 0 1-1.177-1.177l.935-4.673A9.93 9.93 0 0 1 4.968 4.968");
}

</style>
