<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udwa2eg7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:laptop-lock" /></template>
<style>
.udwa2eg7q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.875 3.75h-9.75q-3.375 0-3.375 3.375v5.75q0 3.375 3.375 3.375h9.75q3.375 0 3.375-3.375v-5.75q0-3.375-3.375-3.375m-5.625 5.5V9q0-.75.75-.75t.75.75v.25zm3 .497q.139.106.268.235q.732.732.732 1.768t-.732 1.768t-1.768.732h-1.5q-2.5 0-2.5-2.5q0-1.581 1-2.162V9q0-2.25 2.25-2.25T14.25 9zm8 8.753q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
