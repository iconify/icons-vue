<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bghx64fni"/><path class="q1f5o_hjf"/><path class="wfez5buey"/><path class="dm_5cd1rl"/><path class="dsfkxbb_x"/><path class="d3tw-1bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-zizmor" /></template>
<style>
.bghx64fni {
  fill: var(--svg-color--8767ac, #8767ac);
  d: path("M30 2.78C14.54 2.78 2.78 14.54 2.78 30h13.25c0-7.71 6.26-13.97 13.97-13.97z");
}

.d3tw-1bvg {
  fill: var(--svg-color--226798, #226798);
  d: path("M11.4 30h2.33c0-9 7.28-16.28 16.27-16.3v-2.33A18.63 18.63 0 0 0 11.4 30");
}

.dm_5cd1rl {
  fill: var(--svg-color--ffcb4c, #ffcb4c);
  d: path("M6.73 30h2.33A20.97 20.97 0 0 1 30 9.03V6.7A23.3 23.3 0 0 0 6.73 30");
}

.dsfkxbb_x {
  fill: var(--svg-color--5c903f, #5c903f);
  d: path("M9.06 30h2.34A18.63 18.63 0 0 1 30 11.37V9.03A20.97 20.97 0 0 0 9.06 30");
}

.q1f5o_hjf {
  fill: var(--svg-color--eb2027, #eb2027);
  d: path("M2 30h2.37a25.63 25.63 0 0 1 25.6-25.63V2A28 28 0 0 0 2 30");
}

.wfez5buey {
  fill: var(--svg-color--f19020, #f19020);
  d: path("M4.4 30h2.33A23.3 23.3 0 0 1 30 6.7V4.37A25.63 25.63 0 0 0 4.4 30");
}

</style>
