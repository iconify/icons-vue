<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hs5q88yrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-person-20-filled" /></template>
<style>
.hs5q88yrh {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v3.401a3 3 0 0 0-1-.36V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v4h3.5a.5.5 0 0 1 .5.5c.03 1.176.838 2 2 2s1.968-.824 2-2a.5.5 0 0 1 .5-.5h.764a3 3 0 0 0-.764 2c0 .773.293 1.478.773 2.01A2.5 2.5 0 0 0 11 16.5c0 .151.033.321.088.5H6a3 3 0 0 1-3-3zm14.5 6a2 2 0 1 1-4 0a2 2 0 0 1 4 0m1.5 4.5c0 1.245-1 2.5-3.5 2.5S12 17.75 12 16.5a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5");
}

</style>
