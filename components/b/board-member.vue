<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmkrgbgzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:board-member" /></template>
<style>
.xmkrgbgzv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6q0-1.76 1.245-3.005T12 1.75t3.005 1.245T16.25 6t-1.245 3.005T12 10.25T8.995 9.005T7.75 6M12 11.5q-7.75 0-7.75 4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146Q5.75 13 12 13t6.25 2.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4-7.75-4m-6.217 8.155l.174-.566Q6.446 17.5 8.108 17.5h7.784q1.662 0 2.151 1.589l.174.566q.297.967-.304 1.781t-1.613.814H7.7q-1.012 0-1.613-.814t-.304-1.781");
}

</style>
