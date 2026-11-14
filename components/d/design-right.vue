<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wenv-rrrx"/><path class="b_hi3zb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:design-right" /></template>
<style>
.b_hi3zb4z {
  d: path("M3 6.75L11 11l8-4.25M11 11v9m4-2a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wenv-rrrx {
  d: path("m12.329 19.294l-.625.332q-.163.086-.341.131q-.179.044-.363.044t-.363-.044q-.178-.045-.341-.131l-6.5-3.453q-.09-.048-.172-.107q-.083-.059-.156-.129q-.074-.07-.138-.15q-.063-.079-.116-.166q-.052-.087-.092-.181q-.04-.093-.068-.191q-.027-.098-.04-.199Q3 14.95 3 14.848V7.652q0-.102.014-.202q.013-.101.04-.199t.068-.191t.092-.181q.053-.087.116-.166q.064-.08.138-.15q.073-.07.156-.129q.082-.059.172-.107l6.5-3.453q.163-.086.341-.131q.179-.044.363-.044t.363.044t.341.131l6.5 3.453q.09.048.172.107q.083.059.156.129q.074.07.138.15q.063.079.116.166q.052.087.092.181q.04.093.068.191q.027.098.04.199q.014.1.014.202v4.594");
}

</style>
