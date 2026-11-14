<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5djmbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cart-flatbed-store" /></template>
<style>
.zv5djmbkh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.25 14.326q1.5.337 1.5 2.174q0 2.162-2.077 2.247q.077.338.077.753q0 2.25-2.25 2.25t-2.25-2.25q0-.413.076-.75H8.674q.076.337.076.75q0 2.25-2.25 2.25T4.25 19.5q0-.415.077-.753Q2.25 18.662 2.25 16.5q0-.932.659-1.591q.641-.641 1.541-.659q-.2-.458-.2-1v-4q0-2.5 2.5-2.5h6.5q1.036 0 1.768.732t.732 1.768v4q0 .541-.2 1h3.2V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
