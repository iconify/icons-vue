<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on6p3ibal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-spark-rounded" /></template>
<style>
.on6p3ibal {
  fill: currentColor;
  d: path("M17.98 10.116q-.15 0-.2-.15q-.36-1.391-1.358-2.388q-.997-.997-2.387-1.359q-.15-.05-.15-.2q0-.169.15-.2q1.39-.355 2.387-1.355t1.359-2.391q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.36q.15.024.15.2q0 .15-.15.2q-1.39.36-2.387 1.358q-.998.997-1.36 2.388q-.024.15-.2.15m-8.422 3.011l-6.46 2.602q-.407.154-.753-.083T2 14.983v-.36q0-.196.087-.369t.246-.283l7.225-5.09V4.442q0-.595.423-1.018Q10.405 3 11 3t1.018.424t.424 1.018v4.439l7.225 5.09q.159.11.246.283t.087.37v.359q0 .425-.345.663t-.753.083l-6.46-2.602v4.33l2.575 1.82q.128.094.2.227t.072.29v.35q0 .327-.25.515t-.556.095L11 19.692l-3.483 1.062q-.308.092-.557-.095t-.249-.515v-.355q0-.149.072-.283t.2-.229l2.575-1.82z");
}

</style>
