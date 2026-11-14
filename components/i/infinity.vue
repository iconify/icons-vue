<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag0b2qb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infinity" /></template>
<style>
.ag0b2qb_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 15.75q2.721 0 4.75-2.486q2.029 2.486 4.75 2.486q4 0 4-3.75t-4-3.75q-2.721 0-4.75 2.486Q9.971 8.25 7.25 8.25q-1.666 0-2.834 1.105Q3.25 10.458 3.25 12q0 1.754.875 2.688q.996 1.062 3.125 1.062m0-6q2.158 0 3.833 2.25q-1.675 2.25-3.833 2.25q-1.381 0-1.999-.687Q4.75 13.007 4.75 12q0-.896.697-1.555q.734-.695 1.803-.695m9.5 4.5q-2.158 0-3.833-2.25q1.675-2.25 3.833-2.25q2.5 0 2.5 2.25t-2.5 2.25");
}

</style>
