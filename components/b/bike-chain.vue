<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxw78334b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-chain" /></template>
<style>
.cxw78334b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.782 8.032l8.25-2.5q3.25-.968 5.966 1.056T21.714 12t-2.716 5.412t-5.962 1.057l-8.254-2.501l-.06-.022Q2.049 14.878 2.049 12t2.673-3.946zM15 8q-4 0-4 4t4 4q1.657 0 2.828-1.172Q19 13.657 19 12t-1.172-2.828Q16.657 8 15 8m-8.74 3.25h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.5 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
