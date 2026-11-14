<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl9ne2bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-revert" /></template>
<style>
.bl9ne2bvu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.311 7.25L7.53 5.03q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q7.074 3.75 7 3.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-3.5 3.5q-.106.105-.163.243T2.75 8l.001.039q.007.139.064.266q.056.127.155.225v.001l3.5 3.499q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243L5.311 8.75H15.5q1.968 0 3.359 1.391T20.25 13.5t-1.391 3.359T15.5 18.25h-3.56q-.345-2-2.69-2q-2.75 0-2.75 2.75t2.75 2.75q2.345 0 2.69-2h3.56q2.589 0 4.419-1.831q1.831-1.83 1.831-4.419t-1.831-4.419T15.5 7.25z");
}

</style>
