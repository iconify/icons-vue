<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kknjmqd1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dustpan" /></template>
<style>
.kknjmqd1c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 4q0-2.25-2.25-2.25T9.75 4v6.5q0 .413.076.75H8.111q-1.587 0-2.263 1.436l-2.353 5q-.585 1.243.152 2.404t2.111 1.16h12.484q1.374 0 2.111-1.16q.737-1.161.152-2.404l-2.353-5q-.676-1.436-2.263-1.436h-1.715q.076-.337.076-.75zm3 13.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
