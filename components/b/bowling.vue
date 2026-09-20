<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dqi94gbat"/><path class="nna4tdb5u"/><path class="vl3eyobzp"/><path class="zpnh5k2zv"/><circle class="c3xhbhiwr"/><circle class="v5h2o1bun"/><circle class="tt0e81bec"/><circle class="j6szxp7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bowling" /></template>
<style>
.c3xhbhiwr {
  cx: 12.562px;
  cy: 23.438px;
  r: 12.562px;
  fill: var(--svg-color--31373d, #31373d);
}

.dqi94gbat {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22 10c0-1 1-3 1-5s0-3-1-4s-2-1-2-1s-1 0-2 1s-1 2-1 4s1 4 1 5c0 3-4 5-4 9.084C14 22.417 16 29 17 31h6c1-2 3-8.583 3-11.916C26 15 22 13 22 10");
}

.j6szxp7on {
  cx: 11.431px;
  cy: 28.053px;
  r: 2.316px;
}

.nna4tdb5u {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M18 10h4c0-.475.227-1.18.464-2h-4.927c.236.82.463 1.525.463 2m5.902 4c-.494-.681-.976-1.333-1.332-2h-5.139c-.357.667-.839 1.319-1.332 2z");
}

.tt0e81bec {
  cx: 6.505px;
  cy: 20.938px;
  r: 2.316px;
}

.v5h2o1bun {
  cx: 12.915px;
  cy: 18.79px;
  r: 2.316px;
}

.vl3eyobzp {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M32 13c0-1 1-3 1-5s0-3-1-4s-2-1-2-1s-1 0-2 1s-1 2-1 4s1 4 1 5c0 3-4 5-4 9.084C24 25.417 26 32 27 34h6c1-2 3-8.583 3-11.916C36 18 32 16 32 13");
}

.zpnh5k2zv {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M28 13h4c0-.475.227-1.18.464-2h-4.927c.236.82.463 1.525.463 2m5.902 4c-.494-.681-.976-1.333-1.332-2h-5.139c-.357.667-.839 1.319-1.332 2z");
}

</style>
