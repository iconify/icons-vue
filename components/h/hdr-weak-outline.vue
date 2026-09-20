<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t44bfbcbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hdr-weak-outline" /></template>
<style>
.t44bfbcbh {
  fill: currentColor;
  d: path("M2.175 14.825Q1 13.65 1 12t1.175-2.825T5 8t2.825 1.175T9 12t-1.175 2.825T5 16t-2.825-1.175M12.75 16.25Q11 14.5 11 12t1.75-4.25T17 6t4.25 1.75T23 12t-1.75 4.25T17 18t-4.25-1.75m7.075-1.425Q21 13.65 21 12t-1.175-2.825T17 8t-2.825 1.175T13 12t1.175 2.825T17 16t2.825-1.175");
}

</style>
