<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c6nzncbec"/><path class="o1uip5igp"/><path class="jxwvru9ya"/><path class="dovvg6bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vscode-test-opened" /></template>
<style>
.c6nzncbec {
  fill: var(--svg-color--d32626, #d32626);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.dovvg6bzk {
  fill: var(--svg-color--1f9cf0, #1f9cf0);
  d: path("M25.933 30.871a1.31 1.31 0 0 1-1.491-.254a.768.768 0 0 0 1.311-.543V11.047a.768.768 0 0 0-1.311-.543a1.31 1.31 0 0 1 1.491-.254l4.324 2.079A1.31 1.31 0 0 1 31 13.512v14.1a1.31 1.31 0 0 1-.743 1.183Z");
}

.jxwvru9ya {
  fill: var(--svg-color--007acc, #007acc);
  d: path("m30.257 28.788l-4.324 2.082a1.31 1.31 0 0 1-1.492-.253L10.285 17.71a.875.875 0 0 1-.057-1.236l.057-.057l1.157-1.052a.87.87 0 0 1 1.116-.049l17.049 12.932A.868.868 0 0 0 31 27.556v.05a1.31 1.31 0 0 1-.743 1.182");
}

.o1uip5igp {
  fill: var(--svg-color--0065a9, #0065a9);
  d: path("m30.257 12.333l-4.324-2.082a1.31 1.31 0 0 0-1.492.253L10.285 23.411a.875.875 0 0 0-.057 1.236l.057.057l1.157 1.052a.87.87 0 0 0 1.116.049l17.049-12.932a.868.868 0 0 1 1.393.692v-.05a1.31 1.31 0 0 0-.743-1.182");
}

</style>
