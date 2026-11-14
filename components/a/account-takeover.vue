<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uktty-o3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-takeover" /></template>
<style>
.uktty-o3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.641 4.141Q7.25 5.532 7.25 7.5t1.391 3.359T12 12.25t3.359-1.391T16.75 7.5t-1.391-3.359T12 2.75T8.641 4.141M12 13.75q1.702 0 3.136.402q-.419.563-.562 1.403q-1.176-.305-2.574-.305q-3.193 0-5.225 1.591Q4.75 18.425 4.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T4 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 21q0-3.306 2.6-5.341Q8.29 13.75 12 13.75m9.018 3.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
