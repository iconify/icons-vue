<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="kkl5vmbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-play-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kkl5vmbku {
  d: path("m11.447 8.106l4 2a2.116 2.116 0 0 1 0 3.788l-4 2a2.5 2.5 0 0 1-1.119.278c-.427 0-.855-.155-1.112-.508A1.13 1.13 0 0 1 9 15V9c0-.239.075-.47.216-.664c.257-.353.685-.508 1.112-.508c.39 0 .771.104 1.119.278M11 10.118v3.764l3.553-1.776a.12.12 0 0 0 .065-.106a.12.12 0 0 0-.065-.106Z");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
