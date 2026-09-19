<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ozgz-udqr"/><g class="n1mjunbsu"><path class="yzq1pm-da"/><path class="y_c0a8trj"/><circle class="bfltnkmbz"/><circle class="gumjaibzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:cinema" /></template>
<style>
.bfltnkmbz {
  cx: 25.374px;
  cy: 16.186px;
  r: 9.215px;
}

.gumjaibzf {
  cx: 49.592px;
  cy: 16.186px;
  r: 9.213px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.ozgz-udqr {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 57.1a6.9 6.9 0 0 1-6.898 6.904H6.892c-3.808 0-6.894-3.091-6.894-6.904V6.9c0-3.81 3.086-6.9 6.894-6.9h50.21A6.9 6.9 0 0 1 64 6.9z");
}

.y_c0a8trj {
  d: path("M53.09 46.806c0 5.424-3.835 9.819-8.562 9.819h-14.09c-4.726 0-8.561-4.396-8.561-9.819V36.19c0-5.424 3.835-9.819 8.561-9.819h14.09c4.727 0 8.562 4.396 8.562 9.819z");
}

.yzq1pm-da {
  d: path("M9.06 27.369c-1.686.131-3.091 1.01-3.706 2.201v23.855c.617 1.198 2.028 2.073 3.717 2.207l16.3-14.08L9.06 27.373");
}

</style>
