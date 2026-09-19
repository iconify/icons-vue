<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x9w16mbjj"/><path class="lkrngvbxy"/><path class="zdtoxnb8b"/><path class="r_vyxum1r"/><path class="bpszdhbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:level-slider" /></template>
<style>
.bpszdhbsj {
  fill: var(--svg-color--c7e755, #c7e755);
  d: path("M53 40H39c-4 0-4-6 0-6h14c4 0 4 6 0 6m-2 10H39c-4 0-4-6 0-6h12c4 0 4 6 0 6m-2 10H39c-4 0-4-6 0-6h10c4 0 4 6 0 6");
}

.lkrngvbxy {
  fill: var(--svg-color--6d7275, #6d7275);
  d: path("M6.6 42h20.8c2.5 0 4.6-2.3 4.6-5s-2.1-5-4.6-5H6.6C4.1 32 2 34.3 2 37s2.1 5 4.6 5");
}

.r_vyxum1r {
  fill: var(--svg-color--5b636b, #5b636b);
  d: path("M59 10H39c-4 0-4-6 0-6h20c4 0 4 6 0 6m-2 10H39c-4 0-4-6 0-6h18c4 0 4 6 0 6m-2 10H39c-4 0-4-6 0-6h16c4 0 4 6 0 6");
}

.x9w16mbjj {
  fill: var(--svg-color--333, #333);
  d: path("M14 4.5v55c0 3.4 6 3.4 6 0v-55c0-3.3-6-3.3-6 0");
}

.zdtoxnb8b {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M6.9 39.6h20.2c2.4 0 4.5-1.7 4.5-3.8s-2-3.8-4.5-3.8H6.9c-2.4 0-4.5 1.7-4.5 3.8s2 3.8 4.5 3.8");
}

</style>
