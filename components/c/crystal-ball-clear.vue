<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8jraccgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crystal-ball-clear" /></template>
<style>
.i8jraccgd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10q0-3.417 2.416-5.834T12 1.75t5.834 2.416Q20.25 6.583 20.25 10t-2.416 5.834q-.539.538-1.127.956q.106.159.198.341l.641 1.284q.574 1.149-.101 2.242q-.676 1.093-1.961 1.093H8.516q-1.285 0-1.961-1.093q-.675-1.093-.101-2.242l.641-1.283q.092-.183.198-.342q-.588-.418-1.127-.956Q3.75 13.417 3.75 10m6.454-4.934Q6.75 6.324 6.75 10q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.25 10q0-2.626 2.468-3.524q.14-.051.25-.152t.173-.236t.069-.284t-.044-.289q-.025-.07-.064-.133q-.038-.063-.088-.118t-.11-.098t-.126-.075q-.067-.031-.139-.049q-.071-.017-.145-.02q-.074-.004-.147.008q-.073.011-.143.036");
}

</style>
