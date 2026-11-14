<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_qy5bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gas-boiler" /></template>
<style>
.ze_qy5bjj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.125 1.75h-4.25q-2.123 0-3.624 1.501T4.75 6.875v6.75q0 2.123 1.501 3.624q.89.89 1.999 1.252V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.751l.125.001h4.25l.125-.001V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.999q1.109-.362 1.999-1.252q1.501-1.501 1.501-3.624v-6.75q0-2.123-1.501-3.624T14.125 1.75M12.53 4.97Q16 8.439 16 12q0 1.657-1.172 2.828Q13.657 16 12 16q-4 0-4-4q0-3.561 3.47-7.03q.105-.106.243-.163T12 4.75t.287.057t.243.163");
}

</style>
