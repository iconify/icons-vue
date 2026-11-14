<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awxs8_zpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-phone" /></template>
<style>
.awxs8_zpq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75h5q1.76 0 3.005 1.245T21.25 6v10q0 1.76-1.245 3.005T17 20.25h-4.025q-1.089 2-3.975 2q-4.717 0-4.984-5.564q-1.766-.335-1.766-2.436v-7.5q0-2.5 2.5-2.5t2.5 2.5v7.5q0 2.08-1.731 2.429Q5.76 20.75 9 20.75q1.358 0 2.109-.586q-1.197-.242-2.114-1.159Q7.75 17.76 7.75 16V6q0-1.76 1.245-3.005T12 1.75m5.5 4h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-3 4q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75t-2.75-2.75");
}

</style>
