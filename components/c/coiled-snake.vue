<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yzr8b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coiled-snake" /></template>
<style>
.m0yzr8b_l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.102 6.306q-2.248.41-2.767 3.807q-.242 1.585.262 2.663q.456.974 1.403.974h8q2.25 0 2.25 2.25T17 18.25H6q-.75 0-.75.75t.75.75h13q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-2.25 0-2.25-2.25T6 16.75h11q.75 0 .75-.75t-.75-.75H9q-1.902 0-2.761-1.839q-.697-1.49-.387-3.524q.719-4.702 4.226-5.1Q10.502 3 13.25 3q2.719 0 3.163 1.75H18.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.087Q15.969 8 13.25 8q-2.675 0-3.148-1.694");
}

</style>
