<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ngpmpqbbo"/><ellipse class="srymbl2wh"/><ellipse class="elc89b2ii"/><path class="c5ma8_79w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-raised-eyebrow" /></template>
<style>
.c5ma8_79w {
  fill: var(--svg-color--664500, #664500);
  d: path("M7.102 12.559a1 1 0 0 0 .885.135c4.187-1.355 7.027.554 7.146.636a1.003 1.003 0 0 0 1.39-.25a1 1 0 0 0-.241-1.388c-.15-.106-3.736-2.575-8.91-.901a.998.998 0 0 0-.27 1.768M25 26H11a1 1 0 1 1 0-2h14a1 1 0 1 1 0 2m5.001-15.592c-.368 0-.731-.161-.979-.471c-1.395-1.751-4.299-3.287-5.314-3.287c-.642 0-1.925.911-2.604 1.568a1.251 1.251 0 0 1-1.743-1.794c.391-.38 2.436-2.275 4.347-2.275c2.005 0 5.538 2.056 7.27 4.229a1.25 1.25 0 0 1-.977 2.03");
}

.elc89b2ii {
  cx: 24px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.ngpmpqbbo {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18");
}

.srymbl2wh {
  cx: 12px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 2.75px;
}

</style>
