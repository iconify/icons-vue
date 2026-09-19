<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><path class="w69k5qbny"/><path class="c08vg5-xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:litter-in-bin-sign" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.c08vg5-xm {
  d: path("m20 37l3-3l3 4l-4 2zm25-14H33c-1 0-2 1-2 2l-1 4l-5 3l1 2l6-2l2-5l1 24h3l1-13l1 13h3l1-24l1 9h3l-1-11c0-1-1-2-2-2m-2-4c0 1-1 2-2 2h-4c-1 0-2-1-2-2v-4c0-1 1-2 2-2h4c1 0 2 1 2 2z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.w69k5qbny {
  d: path("m28 38l-1 10h-8l-1-10h-2v13h14V38z");
}

</style>
