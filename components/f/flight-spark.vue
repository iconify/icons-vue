<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2nhcxbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-spark" /></template>
<style>
.l2nhcxbkq {
  fill: currentColor;
  d: path("M17.98 10.116q-.15 0-.2-.15q-.36-1.391-1.358-2.388q-.997-.997-2.387-1.359q-.15-.05-.15-.2q0-.175.15-.2q1.39-.361 2.387-1.358t1.359-2.388q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.998.997-1.36 2.388q-.024.15-.2.15M6.713 21v-1.538l2.846-2.004v-4.331L2 16.173v-1.961L9.558 8.88V4.442q0-.594.424-1.018T11 3t1.018.424t.424 1.018v4.439L20 14.21v1.962l-7.558-3.046v4.33l2.827 2.005V21L11 19.692z");
}

</style>
