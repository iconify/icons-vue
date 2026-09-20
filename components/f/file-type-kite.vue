<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="icf6k-vie"/><path class="jn3u7ub4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-kite" /></template>
<style>
.icf6k-vie {
  fill: var(--svg-color--acb1da, #acb1da);
  d: path("m16.235 13.059l-4.525 8.516L21.575 30l3.249-12.561z");
}

.jn3u7ub4z {
  fill: var(--svg-color--acb1da, #acb1da);
  d: path("m12.751 2l-7.81 13.792l5.991 5.113l4.996-8.824l9.158 4.362l1.973-7.629z");
}

</style>
