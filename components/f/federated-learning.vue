<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqag54b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:federated-learning" /></template>
<style>
.vqag54b-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 1.75h-2.5q-2.5 0-2.5 2.5v1q0 2.5 2.5 2.5h.5v1.804Q9 9.902 9 12.5q0 .674.152 1.197L6.725 15.75H4.25q-1.036 0-1.768.732T1.75 18.25v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.396-.779-2.012l1.516-1.283q.734.545 2.013.545t2.013-.545l1.516 1.283q-.779.616-.779 2.012v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768t-1.768-.732h-2.475l-2.427-2.053Q15 13.174 15 12.5q0-2.598-2.25-2.946V7.75h.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768T13.25 1.75");
}

</style>
