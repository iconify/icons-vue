<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wst-aqbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:handheld-camera" /></template>
<style>
.wst-aqbni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 6.25h-1.75V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 3.25 10 3.25H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 4v2.884q-.399.254-.755.611Q2.25 8.74 2.25 10.5v2q0 1.76 1.245 3.005T6.5 16.75h.25v3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.756q1.6-.083 2.755-1.239q.388-.387.654-.824q.678.569 1.591.569h1.5q1.036 0 1.768-.732t.732-1.768v-2.5q0-1.036-.732-1.768T19.25 7.75h-1.5q-1.058 0-1.668.448q-.244-.37-.577-.703Q14.26 6.25 12.5 6.25m-1.25 10.5v3h-3v-3zM6.5 6.25q-.387 0-.75.06V4.75h3.5v1.5z");
}

</style>
