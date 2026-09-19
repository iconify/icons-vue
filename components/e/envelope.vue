<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a7una-5fk"/><path class="gh-bwpbzh"/><path class="j3283bb3s"/><path class="tr89g6bnq"/><path class="pjyvwib5j"/><path class="y9h7xubbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:envelope" /></template>
<style>
.a7una-5fk {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M63.891 49.29c0 5.698-4.621 10.32-10.322 10.32h-43.25c-5.702 0-10.324-4.622-10.324-10.32V15.27c0-5.7 4.622-10.324 10.324-10.324h43.24c5.701 0 10.322 4.624 10.322 10.324v34.02");
}

.gh-bwpbzh {
  fill: var(--svg-color--silver, silver);
  d: path("M21.505 32.475c6.563-6.746 3.647-3.833 10.321-10.324h.237c5.083 4.938 4.306 4.549 10.323 10.324l21.505 16.814c0 5.698-4.621 10.32-10.322 10.32h-43.25c-5.702 0-10.324-4.622-10.324-10.32L21.5 32.475");
}

.j3283bb3s {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M22.779 34.18c5.762-5.759 3.203-3.27 9.06-8.815h.206c4.463 4.217 3.779 3.886 9.06 8.815l18.884 14.357c0 4.87-4.06 8.814-9.06 8.814H12.957c-5.01 0-9.06-3.944-9.06-8.814z");
}

.pjyvwib5j {
  fill: var(--svg-color--b2b2b2, #b2b2b2);
  d: path("M63.891 15.269c0-5.7-4.621-10.324-10.322-10.324h-43.25C4.617 4.945-.005 9.569-.005 15.269l31.12 26.444c.227.223.457.444.708.691h.237l.893-.868l30.935-26.27");
}

.tr89g6bnq {
  fill: var(--svg-color--b4b4b5, #b4b4b5);
  d: path("M20.503 35.17c.193.065 11.441 7.625 11.441 7.625l11.598-7.625l-2.241-1.922l-4.988 3.971l-4.289 2.561l-1.472-.297l-5.89-4.568l-3.01-2.111l-1.153 2.366");
}

.y9h7xubbb {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M60.04 15.619c0-5.01-4.064-9.08-9.08-9.08H12.93c-5.01 0-9.08 4.064-9.08 9.08l27.368 23.256c.199.194.403.389.625.607h.206c.281-.275.541-.523.784-.764l27.21-23.1");
}

</style>
