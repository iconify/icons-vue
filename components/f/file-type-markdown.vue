<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kw5uikb2l"/><path class="t0ox62biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-markdown" /></template>
<style>
.kw5uikb2l {
  fill: none;
  stroke: var(--svg-color--755838, #755838);
  d: path("M2.5 7.955h27v16.091h-27z");
}

.t0ox62biv {
  fill: var(--svg-color--755838, #755838);
  d: path("M5.909 20.636v-9.272h2.727l2.728 3.409l2.727-3.409h2.727v9.272h-2.727v-5.318l-2.727 3.409l-2.728-3.409v5.318zm17.046 0l-4.091-4.5h2.727v-4.772h2.727v4.772h2.727z");
}

</style>
