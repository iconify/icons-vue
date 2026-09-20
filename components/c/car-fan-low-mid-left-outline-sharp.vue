<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fptwp-bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-low-mid-left-outline-sharp" /></template>
<style>
.fptwp-bhq {
  fill: currentColor;
  d: path("m14.198 22l-2.996-4.308H3.577l-1.42-7.032q-.147-.777.356-1.372t1.28-.596q.56 0 1.005.387t.637 1.03l1.623 5.641h4.34l3.66 5.73zM3.481 7.692q-.614 0-1.038-.424T2.02 6.231t.424-1.038t1.038-.424t1.037.424t.424 1.038t-.424 1.037t-1.037.424m9.23 2.212L8.597 5.769l4.116-4.115l.727.675l-2.941 2.94h6.483v.981h-6.464l2.902 2.946zm5.174 8.48L13.75 14.27l.689-.688l2.945 2.921V10h1v6.502l2.883-2.921l.733.688z");
}

</style>
