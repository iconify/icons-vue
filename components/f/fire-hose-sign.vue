<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3vksmd9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-hose-sign" /></template>
<style>
.u3vksmd9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 1.75H6.875q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T17.125 1.75M5.75 11q0-2.175 1.538-3.712Q8.825 5.75 11 5.75t3.712 1.538Q16.25 8.825 16.25 11v5.5q0 1.25 1.25 1.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-2.75 0-2.75-2.75v-1.826l-.038.038Q13.175 16.25 11 16.25t-3.712-1.538Q5.75 13.175 5.75 11");
}

</style>
