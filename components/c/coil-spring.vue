<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixdaaqbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coil-spring" /></template>
<style>
.ixdaaqbsj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 5.5q0-2.75 6.25-2.75t6.25 2.75q0 1.314-1.427 2q1.427.686 1.427 2t-1.427 2q1.427.686 1.427 2t-1.427 2q1.427.686 1.427 2q0 2.75-6.25 2.75T5.75 17.5q0-1.314 1.427-2q-1.427-.686-1.427-2t1.427-2q-1.427-.686-1.427-2t1.427-2q-1.427-.686-1.427-2M7.25 20v1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V20q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
