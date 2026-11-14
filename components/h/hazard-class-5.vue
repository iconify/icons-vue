<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5t-lwdok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hazard-class-5" /></template>
<style>
.v5t-lwdok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.591 3.031l7.378 7.378q.66.659.66 1.591t-.66 1.591l-7.378 7.378q-.659.66-1.591.66t-1.591-.66l-7.378-7.378q-.66-.659-.66-1.591t.66-1.591l7.378-7.378q.659-.66 1.591-.66t1.591.66M14.75 9.25q0-1.311-2.22-3.53q-.105-.106-.243-.163T12 5.5t-.287.057t-.243.163Q9.25 7.939 9.25 9.25Q9.25 12 12 12t2.75-2.75M9.5 15.5Q9.5 18 12 18q1.036 0 1.768-.732T14.5 15.5t-.732-1.768T12 13q-2.5 0-2.5 2.5");
}

</style>
