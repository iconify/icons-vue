<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qszw-dbbc"/><path class="u6xminppf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-junie-opened" /></template>
<style>
.qszw-dbbc {
  fill: var(--svg-color--f805ff, #f805ff);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.u6xminppf {
  fill: var(--svg-color--47e054, #47e054);
  d: path("M18 12h6v6h-6zm6 6h6v1c0 7-3 11-11 11h-1v-6h1c3.5 0 5-1.5 5-5zm-12 0h6v6h-6z");
}

</style>
