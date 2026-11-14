<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxqurabvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceramic-mug" /></template>
<style>
.pxqurabvo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 3.25H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.25 3.926 3.25 4v12q0 1.968 1.391 3.359T8 20.75h4q1.968 0 3.359-1.391T16.75 16v-.25h.75q3.75 0 3.75-3.75v-1q0-3.75-3.75-3.75h-.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 3.25m1.5 11h-.75v-5.5h.75q2.25 0 2.25 2.25v1q0 2.25-2.25 2.25");
}

</style>
