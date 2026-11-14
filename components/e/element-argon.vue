<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvv8fisjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-argon" /></template>
<style>
.wvv8fisjv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.188 14.427Q8.25 16.145 8.25 17v2.5q0 2.75 3.75 2.75t3.75-2.75V17q0-.855 1.062-2.573Q18.75 11.291 18.75 8.5q0-2.796-1.977-4.773T12 1.75T7.227 3.727T5.25 8.5q0 2.791 1.938 5.927m5.562 1.823H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 17t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 16.25h2.25v-2.554Q9 13.348 9 10.75q0-3 3-3t3 3q0 2.598-2.25 2.946z");
}

</style>
