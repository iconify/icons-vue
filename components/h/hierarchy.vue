<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3vrg6bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hierarchy" /></template>
<style>
.w3vrg6bwt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.75h1q3.25 0 3.25 3.25q0 3.122-3 3.245v3.005h3.75q2.25 0 2.25 2.25v2.258q1.186.082 2.048.944q.952.952.952 2.298t-.952 2.298t-2.298.952h-1q-1.346 0-2.298-.952T14.25 19q0-3.122 3-3.245V13.5q0-.75-.75-.75h-9q-.75 0-.75.75v2.255q3 .123 3 3.245q0 1.346-.952 2.298T6.5 22.25h-1q-1.346 0-2.298-.952T2.25 19t.952-2.298q.862-.862 2.048-.944V13.5q0-2.25 2.25-2.25h3.75V8.245q-3-.123-3-3.245q0-3.25 3.25-3.25");
}

</style>
