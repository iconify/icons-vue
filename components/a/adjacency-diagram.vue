<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf9_lzb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:adjacency-diagram" /></template>
<style>
.cf9_lzb8l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 2.25h-2q-2.5 0-2.5 2.5v2q0 2.5 2.5 2.5h1.815l3.361 5.883q-.926.595-.926 2.117v2q0 1.036.732 1.768T11 21.75h2q1.036 0 1.768-.732t.732-1.768v-2q0-1.522-.926-2.117l3.361-5.883h1.815q1.036 0 1.768-.732t.732-1.768v-2q0-1.036-.732-1.768T19.75 2.25h-2q-2.5 0-2.5 2.5V5h-6.5v-.25q0-2.5-2.5-2.5m10.115 6.724l-3.3 5.776h-2.13l-3.3-5.776Q8.75 8.42 8.75 6.75V6.5h6.5v.25q0 1.67 1.115 2.224");
}

</style>
