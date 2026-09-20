<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n7wm58k4o"/><path class="lyiom025a"/><path class="hssdzabvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-duckdb" /></template>
<style>
.hssdzabvx {
  fill: var(--svg-color--fff100, #fff100);
  d: path("M23.06 13.92h-2.75v4.16h2.75c1.15 0 2.09-.93 2.09-2.08s-.94-2.08-2.09-2.08");
}

.lyiom025a {
  fill: var(--svg-color--fff100, #fff100);
  fill-rule: evenodd;
  d: path("M12.64 21.79c-3.2 0-5.79-2.59-5.79-5.79s2.59-5.79 5.79-5.79c3.21 0 5.79 2.59 5.79 5.79s-2.58 5.79-5.79 5.79");
}

.n7wm58k4o {
  fill: var(--svg-color--1a1a1a, #1a1a1a);
  fill-rule: evenodd;
  d: path("M16 30C8.26 30 2 23.74 2 16S8.26 2 16 2s14 6.26 14 14s-6.26 14-14 14");
}

</style>
