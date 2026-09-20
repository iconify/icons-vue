<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p0o_90scg"/><path class="l04o74b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-kite" /></template>
<style>
.l04o74b5k {
  fill: var(--svg-color--09234c, #09234c);
  d: path("m12.751 2l-7.81 13.792l5.991 5.113l4.996-8.824l9.158 4.362l1.973-7.629z");
}

.p0o_90scg {
  fill: var(--svg-color--09234c, #09234c);
  d: path("m16.235 13.059l-4.525 8.516L21.575 30l3.249-12.561z");
}

</style>
