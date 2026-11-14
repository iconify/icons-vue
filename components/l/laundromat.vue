<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlbuwuz3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:laundromat" /></template>
<style>
.nlbuwuz3i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h5.5q1.76 0 3.005 1.245T15.75 6v12q0 1.76-1.245 3.005T11.5 22.25H6q-1.76 0-3.005-1.245T1.75 18V6q0-1.76 1.245-3.005T6 1.75m11.25 2.251v-.002q0-.828.585-1.414q.586-.586 1.415-.586t1.415.586t.585 1.414q.001.829-.585 1.416q-.586.586-1.415.586t-1.415-.586t-.585-1.414M19.5 7.5Q17 7.5 17 10t2.5 2.5T22 10t-2.5-2.5");
}

</style>
