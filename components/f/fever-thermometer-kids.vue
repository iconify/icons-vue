<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v620mcbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fever-thermometer-kids" /></template>
<style>
.v620mcbkh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 13.941q-1.216 1.303-1.249 3.127q-.037 1.993 1.36 3.415q1.396 1.422 3.389 1.422t3.389-1.422t1.36-3.415q-.033-1.824-1.249-3.127V5.25q0-3.5-3.5-3.5t-3.5 3.5zM12.75 17q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 17V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 6.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
