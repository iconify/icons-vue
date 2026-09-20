<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qunug201q"/><path class="rqw8jrx0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-registry" /></template>
<style>
.qunug201q {
  fill: var(--svg-color--1b8c98, #1b8c98);
  d: path("M23.492 2H30v6.508h-6.508ZM11.477 7.363L15.3 2.1l5.265 3.825l-3.825 5.265Zm9 5.559l6.154-2.122l2.119 6.153l-6.15 2.122Z");
}

.rqw8jrx0r {
  fill: var(--svg-color--4ed1f8, #4ed1f8);
  d: path("M2 8.453h6.508v6.508H2ZM2 16h6.508v6.508H2Zm7.492 0H16v6.508H9.492ZM2 23.492h6.508V30H2Zm7.492 0H16V30H9.492Zm7.547 0h6.508V30h-6.508Z");
}

</style>
