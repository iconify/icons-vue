<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1asz6uhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:7k-plus-outline-sharp" /></template>
<style>
.i1asz6uhp {
  fill: currentColor;
  d: path("M7.52 14.692h.98l1.508-4.469v-.915H6.173v.884h2.88zm3.634 0h.884v-2.365l2.289 2.365h1.229l-2.652-2.73l2.652-2.654h-1.19l-2.328 2.327V9.308h-.884zm5.577-.807h.769v-1.5H19v-.77h-1.5v-1.5h-.77v1.5h-1.5v.77h1.5zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
