<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":253};
const content = `<defs><linearGradient id="SVG7xrvve2n" x1="90.642%" x2="12.543%" y1="10.337%" y2="88.429%"><stop offset="0%" class="tq9v7qyki"/><stop offset="3%" class="anel5ybyk"/><stop offset="23%" class="vw4ih9b2q"/><stop offset="43%" class="h8pq6woqr"/><stop offset="61%" class="oolc10biq"/><stop offset="77%" class="sfivzrbka"/><stop offset="90%" class="gu1vsna2b"/><stop offset="100%" class="m8jxpxbpl"/></linearGradient></defs><path fill="url(#SVG7xrvve2n)" class="vnq1r9s0y"/><path class="rv0-d9cqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:async-api-icon" /></template>
<style>
.anel5ybyk {
  stop-color: var(--svg-color--27cdfc, #27cdfc);
  stop-opacity: 96;
}

.gu1vsna2b {
  stop-color: var(--svg-color--a42ee3, #a42ee3);
  stop-opacity: 13;
}

.h8pq6woqr {
  stop-color: var(--svg-color--6e73ee, #6e73ee);
  stop-opacity: 49;
}

.m8jxpxbpl {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 10;
}

.oolc10biq {
  stop-color: var(--svg-color--8753e9, #8753e9);
  stop-opacity: 32;
}

.rv0-d9cqt {
  fill: var(--svg-color--fff, #fff);
  d: path("m75.025 110.118l7.62-10.373l59.916 42.96l-7.62 10.373zm38.47 0l7.62-10.373l59.915 42.96l-7.619 10.373zm14.551-63.467c-31.617 0-57.451 19.025-58.472 42.698l-.031 1.95h13.009v-.494c0-17.277 20.443-31.34 45.532-31.34s45.531 14.063 45.531 31.34v.495h13.01v-.495c-.075-24.345-26.316-44.154-58.579-44.154m45.44 115.423c0 17.276-20.444 31.34-45.551 31.34s-45.532-14.064-45.532-31.34v-.496H69.394v.496c0 24.344 26.24 44.154 58.503 44.154c31.618 0 57.452-19.025 58.473-42.699l.032-1.95h-13.01z");
}

.sfivzrbka {
  stop-color: var(--svg-color--993ce5, #993ce5);
  stop-opacity: 20;
}

.tq9v7qyki {
  stop-color: var(--svg-color--21d4fd, #21d4fd);
}

.vnq1r9s0y {
  d: path("M195.452 0H60.548C27.108 0 0 26.78 0 59.814v133.268c0 33.035 27.108 59.814 60.548 59.814h134.904c33.44 0 60.548-26.78 60.548-59.814V59.814C256 26.78 228.892 0 195.452 0");
}

.vw4ih9b2q {
  stop-color: var(--svg-color--4e9cf4, #4e9cf4);
  stop-opacity: 70;
}

</style>
