<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud2e68b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:confidence-interval" /></template>
<style>
.ud2e68b3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 18.75q1.86 0 4.675-7.978q.291-.824.576-1.558q.004-.094.032-.185Q9.561 3.25 12 3.25t4.217 5.779q.028.091.032.185q.285.734.576 1.558Q19.64 18.75 21.5 18.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m2.43 0h2.82v-5.246q-1.436 3.565-2.82 5.246m11.32 0h2.82q-1.384-1.681-2.82-5.246z");
}

</style>
