<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<g class="cuyn6tgcc"><path class="slxu3vb6s"/><path class="xvsowwbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-28-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.slxu3vb6s {
  d: path("M14 2v8a2 2 0 0 0 2 2h7.999l.001.078V23.6a2.4 2.4 0 0 1-2.4 2.4H6.4A2.4 2.4 0 0 1 4 23.6V4.4A2.4 2.4 0 0 1 6.4 2z");
}

.xvsowwbqa {
  d: path("M15.5 2.475V10a.5.5 0 0 0 .5.5h7.502a3 3 0 0 0-.307-.366l-7.431-7.431a2.4 2.4 0 0 0-.264-.228");
}

</style>
