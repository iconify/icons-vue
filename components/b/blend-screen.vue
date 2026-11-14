<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heab7bctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blend-screen" /></template>
<style>
.heab7bctq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624v-9.25q0-2.123-1.501-3.624T16.625 2.25M8.25 9.5q0-3.75 3.75-3.75t3.75 3.75q0 .357-.034.681Q18 10.823 18 13.75q0 3.75-3.75 3.75q-1.378 0-2.25-.507q-.872.507-2.25.507Q6 17.5 6 13.75q0-2.927 2.284-3.569q-.034-.324-.034-.681");
}

</style>
