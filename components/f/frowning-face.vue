<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="zqasd_boi"/><ellipse class="kri5l248a"/><path class="u1w4t6sgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:frowning-face" /></template>
<style>
.kri5l248a {
  cx: 24.5px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.u1w4t6sgt {
  fill: var(--svg-color--664500, #664500);
  d: path("M8.665 27.871a.5.5 0 0 0 .635.029c.039-.029 3.922-2.9 8.7-2.9c4.766 0 8.662 2.871 8.7 2.9a.5.5 0 0 0 .729-.657C27.3 27.029 24.212 22 18 22s-9.301 5.028-9.429 5.243a.5.5 0 0 0 .094.628");
}

.zqasd_boi {
  cx: 11.5px;
  cy: 14.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
