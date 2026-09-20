<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="wi60fm2wb"/><path clip-rule="evenodd" class="evpy69biv"/><path class="m16cowbsb"/><path clip-rule="evenodd" class="lx2lj4q7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:fast-forward" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.evpy69biv {
  fill-rule: evenodd;
  d: path("M9.264 10L7 7.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L6.73 4.355C6.111 3.69 5 4.129 5 5.037v9.926c0 .908 1.112 1.346 1.731.682z");
}

.lx2lj4q7w {
  fill-rule: evenodd;
  d: path("M14.264 10L12 7.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L11.73 4.355c-.619-.665-1.73-.226-1.73.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.m16cowbsb {
  d: path("M16.363 9.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V5.037c0-.908 1.112-1.346 1.731-.682z");
}

.wi60fm2wb {
  d: path("M11.363 9.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V5.037c0-.908 1.112-1.346 1.731-.682z");
}

</style>
