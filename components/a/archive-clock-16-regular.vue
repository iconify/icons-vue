<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="phk76cbaz"/><path class="wqtcxgbkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-16-regular" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.phk76cbaz {
  d: path("M16 11.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M11.5 9a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H13a.5.5 0 0 0 0-1h-1V9.5a.5.5 0 0 0-.5-.5");
}

.wqtcxgbkj {
  d: path("M13.5 2A1.5 1.5 0 0 1 15 3.5v1a1.5 1.5 0 0 1-1 1.415v.686a5.5 5.5 0 0 0-1-.393V6H3v5.5A1.5 1.5 0 0 0 4.5 13h1.708q.149.524.394 1H4.5A2.5 2.5 0 0 1 2 11.5V5.915A1.5 1.5 0 0 1 1 4.5v-1A1.5 1.5 0 0 1 2.5 2zm-11 1a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5z");
}

</style>
