<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czu8prspj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:friend-online" /></template>
<style>
.czu8prspj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.141 4.141Q5.75 5.532 5.75 7.5t1.391 3.359T10.5 12.25t3.359-1.391T15.25 7.5t-1.391-3.359T10.5 2.75T7.141 4.141M2.75 21.5q0-3.574 2.334-5.738Q7.255 13.75 10.5 13.75q1.894 0 3.279.554q.068.027.13.067t.115.092t.094.113t.071.129t.045.14t.016.146t-.013.146t-.041.142q-.027.068-.067.13t-.092.115t-.113.094t-.129.071t-.14.045t-.146.016t-.146-.013t-.142-.041q-1.115-.446-2.721-.446q-6.25 0-6.25 6.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m12-3q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75m1.5 0q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25");
}

</style>
