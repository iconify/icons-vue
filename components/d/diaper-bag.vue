<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buu44abwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diaper-bag" /></template>
<style>
.buu44abwj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 8.25h-1.5V5.5q0-2.75-2.75-2.75T5.75 5.5v2.75H4q-.034 0-.068.003q-.148.014-.281.083q-.132.069-.227.184q-.096.114-.14.257q-.044.142-.031.291l.997 10.968q.018 2.214 2.25 2.214h11q2.232 0 2.25-2.214l.997-10.968q.003-.034.003-.068q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 8.25h-1.75V5.5q0-2.75-2.75-2.75T12.75 5.5zM7.25 5.5v2.75h2.5V5.5q0-1.25-1.25-1.25T7.25 5.5m7 2.75V5.5q0-1.25 1.25-1.25t1.25 1.25v2.75zm-3.75 4.5h3q3.25 0 3.25 3.25t-3.25 3.25h-3q-3.25 0-3.25-3.25t3.25-3.25");
}

</style>
