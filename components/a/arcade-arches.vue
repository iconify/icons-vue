<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g38vdnbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arcade-arches" /></template>
<style>
.g38vdnbbo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.5v9.293q-.11.039-.202.109t-.16.165t-.103.206t-.035.227q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.116-.035-.227t-.103-.206q-.067-.095-.16-.165q-.092-.07-.202-.109V8.5q0-3.75-3.75-3.75q-2.073 0-3 1.146q-.927-1.146-3-1.146T9 5.896Q8.073 4.75 6 4.75q-3.75 0-3.75 3.75m13.5 9.25V8.5q0-2.25 2.25-2.25t2.25 2.25v9.25zm-1.5-9.25v9.25h-4.5V8.5q0-2.25 2.25-2.25t2.25 2.25m-6 9.25h-4.5V8.5q0-2.25 2.25-2.25T8.25 8.5z");
}

</style>
