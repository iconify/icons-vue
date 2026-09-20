<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="xlni99bwn"><path class="vjjoc4bqv"/><path class="jwmd-db_n"/></g><g class="t2tey3b0u"><path class="vppu71g0b"/><path class="uwlu1kj9r"/><path class="lc25j2zzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-trunk-opened" /></template>
<style>
.jwmd-db_n {
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.lc25j2zzh {
  d: path("M25.54 21.86h-2a1.76 1.76 0 0 0-3.51 0H18a3.68 3.68 0 0 1 1.09-2.62a3.75 3.75 0 0 1 5.28 0a3.68 3.68 0 0 1 1.09 2.62Z");
}

.t2tey3b0u {
  fill: var(--svg-color--fb6a5b, #fb6a5b);
}

.uwlu1kj9r {
  d: path("M17.35 21.86h-2a6.4 6.4 0 0 1 1.89-4.54a6.52 6.52 0 0 1 4.57-1.88v2a4.45 4.45 0 0 0-3.15 1.31a4.4 4.4 0 0 0-1.31 3.13Z");
}

.vjjoc4bqv {
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.vppu71g0b {
  d: path("M21.81 31v-2a7.3 7.3 0 0 0 4-1.2a7.19 7.19 0 0 0-2.6-13a7.16 7.16 0 0 0-8.59 7h-2a9.16 9.16 0 0 1 5.67-8.44a9.3 9.3 0 0 1 5.31-.52A9.14 9.14 0 0 1 30.82 20a9 9 0 0 1-.52 5.28a9.15 9.15 0 0 1-3.38 4.1A9.33 9.33 0 0 1 21.81 31");
}

.xlni99bwn {
  fill: var(--svg-color--a54646, #a54646);
}

</style>
