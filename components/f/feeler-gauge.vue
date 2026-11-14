<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l73kkoykb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feeler-gauge" /></template>
<style>
.l73kkoykb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.763 18.613v-.001l2.75-14.749q.025-.137.098-.256q.806-1.31 2.319-1.035t1.806 1.785q.027.136.003.272l-1.341 7.662L13.97 6.72q1.655-1.654 3.31 0q1.654 1.655.001 3.31l-5.572 5.572l7.662-1.341q.136-.024.272.003q1.51.293 1.785 1.806t-1.035 2.319q-.119.073-.256.098l-14.75 2.75q-1.165.218-2.004-.62q-.838-.839-.62-2.004");
}

</style>
