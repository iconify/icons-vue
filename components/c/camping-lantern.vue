<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhhitdyyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camping-lantern" /></template>
<style>
.yhhitdyyj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 5.25V4.5q0-3.25 3.25-3.25t3.25 3.25v.75h.25q.149 0 .287.057t.243.163l2.5 2.5q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.105.106-.243.163T18 9.25h-.326q.076.337.076.75v7.5q0 .495-.109.881q1.109.38 1.109 1.869q0 2-2 2h-9.5q-2 0-2-2q0-1.489 1.109-1.869q-.109-.386-.109-.881V10q0-.413.076-.75H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 8.5q0-.149.057-.287t.163-.243l2.5-2.5q.105-.106.243-.163T8.5 5.25zm1.5 0V4.5q0-1.75 1.75-1.75t1.75 1.75v.75zm2.28 5.72q-.105-.106-.243-.163T12 10.75t-.287.057t-.243.163Q9.5 12.939 9.5 14.5Q9.5 17 12 17q1.036 0 1.768-.732T14.5 14.5q0-1.561-1.97-3.53");
}

</style>
