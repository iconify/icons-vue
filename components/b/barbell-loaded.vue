<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwv5c-bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barbell-loaded" /></template>
<style>
.rwv5c-bkz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.218 16.667q-.12.771-.7 1.351q-.732.732-1.768.732t-1.768-.732t-.732-1.768v-8.5q0-2.5 2.5-2.5q2.28 0 2.481 2.08q.344-.08.769-.08q2.25 0 2.25 2.25v1.75h3.5V9.5q0-2.25 2.25-2.25q.432 0 .782.083q.12-.771.7-1.351q.732-.732 1.768-.732t1.768.732t.732 1.768v8.5q0 1.036-.732 1.768t-1.768.732t-1.768-.732q-.58-.58-.7-1.351q-.35.083-.782.083q-2.25 0-2.25-2.25v-1.75h-3.5v1.75q0 2.25-2.25 2.25q-.432 0-.782-.083");
}

</style>
