<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waj4-hq3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-bromine" /></template>
<style>
.waj4-hq3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25m-4.11 3.705q4.735 4.472 4.735 7.545q0 2.175-1.538 3.712Q14.175 18.75 12 18.75t-3.712-1.538Q6.75 15.675 6.75 13.5q0-3.073 4.735-7.545q.052-.049.112-.087q.06-.039.126-.065t.136-.04T12 5.75t.141.013q.07.014.136.04t.126.065q.06.038.112.087");
}

</style>
