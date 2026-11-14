<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elx5wz_nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ape-skull" /></template>
<style>
.elx5wz_nc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2.25q-7.33 0-11.156 6.886q-.05.09-.074.191q-.024.1-.019.203q.004.104.036.202t.089.184l1.746 2.62l-2.278 4.1q-.034.062-.056.129q-.023.068-.032.138t-.005.142t.022.139q.018.069.048.134q.03.064.071.122q.042.057.094.106q.051.049.111.087l5.5 3.5q.185.117.403.117H15q.115 0 .224-.034t.203-.1q.094-.065.165-.155q.07-.09.11-.198l1.377-3.672q4.671-1.725 4.671-6.591q0-3.43-1.995-5.74Q17.588 2.25 14 2.25m-6.75 8Q7.25 7.5 10 7.5t2.75 2.75T10 13t-2.75-2.75");
}

</style>
