<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxxup5rjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biopsy-sample" /></template>
<style>
.uxxup5rjk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 2.25H6.75q-2.5 0-2.5 2.5q0 1.581 1 2.162V19.5q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75V6.912q1-.581 1-2.162q0-2.5-2.5-2.5m-10.5 7.5v-2.5h10.5v2.5zm0 9.75v-8.25h10.5v8.25q0 1.25-1.25 1.25H8q-1.25 0-1.25-1.25m2-3.5q0-1.478 1.09-2.363q1.071-.871 2.533-.627q1.467.245 2.24 1.339q.834 1.182.349 2.638q-.472 1.415-1.914 1.964q-1.314.5-2.577-.005q-.072-.029-.137-.072Q8.75 17.818 8.75 16");
}

</style>
