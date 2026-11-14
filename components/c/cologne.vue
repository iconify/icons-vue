<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqooanbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cologne" /></template>
<style>
.cqooanbce {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2.75h-4Q7.75 2.75 7.75 5v1q0 1.847 1.516 2.178q-.016.153-.016.322q0 .13.01.25H8.125q-3.375 0-3.375 3.375v6.25q0 3.375 3.375 3.375h7.75q3.375 0 3.375-3.375v-6.25q0-3.375-3.375-3.375H14.74q.01-.12.01-.25q0-.193-.021-.364q.477-.16.862-.545q.659-.659.659-1.591V5q0-.932-.659-1.591T14 2.75m1 11.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T15 16H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 14.5z");
}

</style>
