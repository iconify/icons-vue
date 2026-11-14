<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cplh-xn6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cover-level-standard" /></template>
<style>
.cplh-xn6v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 2.75h.75q1.036 0 1.768.732T22 5.25v14q0 1.036-.732 1.768t-1.768.732h-.75q-1.036 0-1.768-.732t-.732-1.768v-14q0-2.5 2.5-2.5m-6.25 6h-.75q-2.5 0-2.5 2.5v8q0 1.036.732 1.768t1.768.732h.75q1.036 0 1.768-.732T15 19.25v-8q0-1.036-.732-1.768T12.5 8.75m-7.75 5.5h.75q1.036 0 1.768.732T8 16.75v2.5q0 1.036-.732 1.768T5.5 21.75h-.75q-1.036 0-1.768-.732T2.25 19.25v-2.5q0-2.5 2.5-2.5");
}

</style>
