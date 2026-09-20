<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_x2s0zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:key" /></template>
<style>
.fe_x2s0zq {
  fill: currentColor;
  d: path("M8.308 13.308q.538-.539.538-1.308t-.538-1.308T7 10.154t-1.308.538T5.154 12t.538 1.308T7 13.846t1.308-.538M7 16.73q-2 0-3.366-1.366Q2.27 14 2.27 12t1.366-3.366T7 7.27q1.698 0 2.941.958t1.593 2.273h9.049l1.494 1.494l-2.48 2.635l-1.828-1.379l-1.827 1.442l-1.557-1.192h-2.85q-.356 1.339-1.608 2.285T7 16.73");
}

</style>
