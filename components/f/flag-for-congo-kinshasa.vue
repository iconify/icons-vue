<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f4htagqjk"/><path class="o6opksb4t"/><path class="swlshvblv"/><path class="debvv0odq"/><path class="xvqkrhbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-congo-kinshasa" /></template>
<style>
.debvv0odq {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M10 10C3.373 10 0 14.925 0 21v19.5L50.243 10zm44 44c6.627 0 10-4.925 10-11V23.543L13.825 54z");
}

.f4htagqjk {
  fill: var(--svg-color--fefe01, #fefe01);
  d: path("M63.973 20.21L8.513 53.875l-.002.03c.476.059.969.094 1.487.094h3.825l50.17-30.457v-2.543c0-.267-.015-.527-.027-.789M.031 43.844l-.002-.024l55.53-33.71c-.5-.065-1.015-.11-1.56-.11h-3.757L.002 40.5V43q.002.426.027.844h.004");
}

.o6opksb4t {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M63.973 20.21v-.01z");
}

.swlshvblv {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M64 20.21v-.008c0-.301-.055-.598-.086-.891c-.004-.037-.016-.075-.02-.112a14 14 0 0 0-.128-.841l-.022-.113a14 14 0 0 0-.184-.83l-.014-.048c-.381-1.47-1.01-2.796-1.879-3.904l-.003-.003a9 9 0 0 0-.528-.611l-.049-.052a9 9 0 0 0-.574-.546l-.049-.043c-1.287-1.101-2.922-1.844-4.903-2.1L.031 43.818q.025.461.076.909l.009.09q.051.428.128.848l.021.115q.078.416.182.819l.021.081c.386 1.459 1.014 2.777 1.884 3.878l.003.005q.247.309.521.597l.063.067q.266.276.557.527l.08.067q.297.253.619.479l.046.03c1.173.81 2.601 1.356 4.255 1.563l55.51-33.683");
}

.xvqkrhbjd {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("m19.308 18.774l-5.582.01l-1.734-5.644l-1.719 5.644l-5.585-.01l4.526 3.436l-1.754 5.614L12 24.34l4.548 3.484l-1.758-5.614z");
}

</style>
