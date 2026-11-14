<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdrvfabjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:candidate-hired" /></template>
<style>
.jdrvfabjj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m11.334 8.273L15.28 11.47q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T14 12t.014.146q.015.073.043.141t.069.13t.094.113l2.5 2.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.045-.045.082-.096l4.25-6q.086-.122.119-.268q.033-.145.008-.292t-.104-.274q-.08-.126-.201-.212q-.061-.043-.128-.073q-.068-.03-.14-.046q-.072-.017-.146-.019q-.073-.002-.146.011t-.142.039t-.132.065t-.116.09t-.096.111zM1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
