<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1n1jsbiv"/><path class="au_tc_b-u"/><path class="e_6toqnfp"/><path class="jv_rsg7cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cursorrules" /></template>
<style>
.au_tc_b-u {
  fill: var(--svg-color--939393, #939393);
  d: path("M16 16V2L3.75 9l24.5 14L16 30L3.75 23");
}

.e_6toqnfp {
  fill: var(--svg-color--e3e3e3, #e3e3e3);
  d: path("M28.25 9H16v21");
}

.jv_rsg7cf {
  fill: var(--svg-color--fff, #fff);
  d: path("M3.75 9h24.5L16 16");
}

.o1n1jsbiv {
  fill: var(--svg-color--444, #444);
  d: path("M3.75 9v14h24.5V9L16 2");
}

</style>
