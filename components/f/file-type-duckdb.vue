<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="av18nnb8s"/><path class="ao1ujkbat"/><path class="jrc2oobby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-duckdb" /></template>
<style>
.ao1ujkbat {
  fill: var(--svg-color--1d1d1b, #1d1d1b);
  fill-rule: evenodd;
  d: path("M12.67 21.75c-3.18 0-5.74-2.57-5.74-5.75s2.56-5.75 5.74-5.75s5.74 2.57 5.74 5.75s-2.56 5.75-5.74 5.75");
}

.av18nnb8s {
  fill: var(--svg-color--fff100, #fff100);
  fill-rule: evenodd;
  d: path("M16 29.89C8.32 29.89 2.11 23.68 2.11 16S8.32 2.11 16 2.11S29.89 8.32 29.89 16S23.68 29.89 16 29.89");
}

.jrc2oobby {
  fill: var(--svg-color--1d1d1b, #1d1d1b);
  d: path("M23.01 13.93h-2.73v4.14h2.73c1.14 0 2.06-.93 2.06-2.07s-.92-2.07-2.06-2.07");
}

</style>
