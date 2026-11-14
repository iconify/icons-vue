<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmq6whgkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-d-cell" /></template>
<style>
.xmq6whgkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.75h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 1.75 14 1.75m-4 2.5h4q1.76 0 3.005 1.245T18.25 8.5V18q0 1.76-1.245 3.005T14 22.25h-4q-1.76 0-3.005-1.245T5.75 18V8.5q0-1.76 1.245-3.005T10 4.25M9 12v5.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2q3.5 0 3.5-3.5t-3.5-3.5h-2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T9 12");
}

</style>
