<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw6o1cbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cell-energy" /></template>
<style>
.yw6o1cbbr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.799 5.769Q1.75 8.337 1.75 12t3.049 6.231Q7.791 20.75 12 20.75t7.201-2.519Q22.25 15.663 22.25 12t-3.049-6.231Q16.209 3.25 12 3.25T4.799 5.769m6.489 1.656q.66-.867 1.656-.424q.995.442.793 1.515l-.173.905q-.062.323.148.576q.209.253.538.253q1.004.001 1.45.899q.446.899-.16 1.698l-2.828 3.728q-.66.867-1.656.424q-.995-.442-.793-1.515l.173-.905q.062-.323-.148-.576q-.209-.253-.538-.253q-1.004-.001-1.45-.899q-.446-.899.16-1.698l2.827-3.727z");
}

</style>
