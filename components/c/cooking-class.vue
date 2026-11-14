<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo1aieb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cooking-class" /></template>
<style>
.oo1aieb1o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 12.697q-2.298-.346-2.436-2.97Q4.168 6.97 6.88 6.352q.552-1.963 2.424-2.65Q10.955 3.097 12 3.9q1.045-.803 2.696-.198q1.872.687 2.424 2.65q2.712.618 2.566 3.375q-.138 2.624-2.436 2.97V19q0 2.75-2.75 2.75h-5q-2.75 0-2.75-2.75zm1.5.053V19q0 1.25 1.25 1.25h5q1.25 0 1.25-1.25v-6.25z");
}

</style>
