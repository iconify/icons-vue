<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gju5cgbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:found-person" /></template>
<style>
.gju5cgbuv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.439 21.998Q4.25 13.91 4.25 9.5q0-3.21 2.27-5.48T12 1.75t5.48 2.27t2.27 5.48q0 4.41-7.189 12.498q-.1.112-.234.177t-.283.074t-.29-.04t-.252-.148q-.033-.03-.063-.063M12 4.75q-2.75 0-2.75 2.75T12 10.25t2.75-2.75T12 4.75m0 6.75q-3.25 0-3.25 3q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-1.5 1.75-1.5t1.75 1.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3-3.25-3");
}

</style>
