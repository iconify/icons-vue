<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alfs5cclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:magnetic-stirrer" /></template>
<style>
.alfs5cclo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 3v5.25h10.5V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T18 2.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v16q0 2.75-2.75 2.75H8q-2.75 0-2.75-2.75V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 2.25 6 2.25t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T6.75 3m0 16q0 1.25 1.25 1.25h8q1.25 0 1.25-1.25V9.75H6.75zm3.5-4h3.5q2 0 2 2t-2 2h-3.5q-2 0-2-2t2-2");
}

</style>
