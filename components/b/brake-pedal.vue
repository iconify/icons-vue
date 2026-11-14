<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s87motbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brake-pedal" /></template>
<style>
.s87motbmz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 1.75h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014H8.75v6.95l4.434 4.656l2.946-1.662q2.146-1.21 3.382.91l.006.01l.005.008q.519.89.249 1.884t-1.166 1.5l-6.736 3.8q-2.146 1.21-3.382-.91l-.011-.018q-.519-.89-.249-1.884t1.166-1.5l2.443-1.378l-4.38-4.599q-.1-.104-.153-.238q-.054-.135-.054-.279V3.25H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.75 2.574 3.75 2.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
