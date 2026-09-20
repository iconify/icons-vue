<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r1mb6vbfi"/><path class="jw_j0qt_b"/><path class="s7zz392-y"/><path class="gj242k_gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:inbox-tray" /></template>
<style>
.gj242k_gm {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M26.716 8h-4.783V2a2 2 0 0 0-2-2h-4.001a2 2 0 0 0-1.999 2v6H9.148c-1.223 0-1.516.623-.651 1.489l7.863 7.863c.865.865 2.28.865 3.146 0l7.863-7.863C28.232 8.623 27.94 8 26.716 8");
}

.jw_j0qt_b {
  fill: var(--svg-color--662113, #662113);
  d: path("M25 20a7 7 0 1 1-14 0z");
}

.r1mb6vbfi {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-9c0-2.209.791-3 3-3h30c2.209 0 3 .791 3 3z");
}

.s7zz392-y {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M4 36h28a4 4 0 0 0 4-4H0a4 4 0 0 0 4 4");
}

</style>
