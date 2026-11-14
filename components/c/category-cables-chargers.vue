<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfh109bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-cables-chargers" /></template>
<style>
.nfh109bqh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 3v2.75h2.5V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.81q1.284.214 2.255 1.185Q16.25 8.24 16.25 10v3q0 1.76-1.245 3.005T12 17.25h-1.25V18q0 2.75 6.25 2.75h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-7.75 0-7.75-4.25v-.75H8q-1.76 0-3.005-1.245T3.75 13v-3q0-1.76 1.245-3.005q.971-.971 2.255-1.185V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q7.926 2.25 8 2.25t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T8.75 3");
}

</style>
