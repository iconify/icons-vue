<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="docr6qbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-clover" /></template>
<style>
.docr6qbxn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.671 7.489q-2.788.305-3.493 3.525q-.869 3.97 2.993 5.237q2.663.874 4.275-.62q.721 3.763 4.085 6.455q.058.046.124.08q.065.034.136.054q.071.021.145.027q.073.007.147-.002q.073-.008.144-.03t.135-.058t.121-.083t.103-.105t.08-.124t.054-.136q.021-.071.027-.145q.007-.073-.002-.147q-.008-.073-.03-.144t-.058-.135t-.083-.121t-.105-.103q-2.598-2.078-3.381-4.871q1.498.945 3.741.208q3.862-1.267 2.993-5.237q-.705-3.22-3.493-3.525q1.158-2.581-1.301-4.818q-3.028-2.754-6.056 0q-2.459 2.237-1.301 4.818");
}

</style>
