<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pukhztb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loyalty-card-pharmacy" /></template>
<style>
.pukhztb2x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 4.25H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T17.125 4.25m-3.913 4.763l.158.474q.17.513.711.513h.568q.929.002 1.237.877q.307.876-.416 1.458l-.454.363q-.399.319-.249.807l.221.716q.278.9-.472 1.472q-.75.571-1.544.064l-.57-.362q-.402-.256-.804 0l-.57.363q-.794.506-1.544-.065q-.75-.572-.472-1.473l.221-.716q.15-.487-.248-.805l-.454-.364q-.724-.582-.417-1.458q.308-.875 1.235-.877h.57q.541 0 .711-.513l.158-.474Q11.079 8.14 12 8.14t1.212.873");
}

</style>
