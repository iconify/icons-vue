<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggjwj5bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:automatic-shifter" /></template>
<style>
.ggjwj5bqq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-3.5 0-3.5 3.5q0 3.102 2.75 3.455v.545H9.375q-2.123 0-3.624 1.501T4.25 14.375v2.75q0 2.123 1.501 3.624t3.624 1.501h5.25q2.123 0 3.624-1.501t1.501-3.624v-2.75q0-2.123-1.501-3.624T14.625 9.25H12.75v-.545q2.75-.353 2.75-3.455q0-3.5-3.5-3.5M12 12q2.25 0 2.25 2.25v3q0 2.25-2.25 2.25t-2.25-2.25v-3Q9.75 12 12 12");
}

</style>
