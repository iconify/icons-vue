<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmd200ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bread-maker" /></template>
<style>
.kmd200ban {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 3.75h10.25q2.123 0 3.624 1.501q.719.72 1.094 1.582q.092.047.168.118q.075.07.129.158q.054.089.082.188q.028.1.028.203q0 .192-.092.36q.092.489.092 1.015v6.75q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 15.625v-6.75q0-.526.092-1.015q-.092-.168-.092-.36q0-.103.028-.203q.028-.099.082-.188q.054-.088.129-.158t.168-.118q.375-.862 1.094-1.582Q4.752 3.75 6.875 3.75M6.75 16.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V14q0-1.817-1.608-3.067Q14.121 9.75 12 9.75t-3.642 1.183Q6.75 12.183 6.75 14z");
}

</style>
