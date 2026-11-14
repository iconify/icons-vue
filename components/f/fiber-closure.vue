<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1qryvz3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fiber-closure" /></template>
<style>
.c1qryvz3g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 10.5v2.278q-1.684.199-1.95 1.815q-2.05.59-2.05 4.907q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.5.638-3.214q.449 1.464 2.362 1.464h11.5q1.913 0 2.362-1.464q.638.714.638 3.214q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.317-2.05-4.907q-.266-1.616-1.95-1.815V10.5q0-2.589-1.831-4.419Q14.589 4.25 12 4.25T7.581 6.081Q5.75 7.911 5.75 10.5m1.5 0q0-1.968 1.391-3.359T12 5.75t3.359 1.391T16.75 10.5v2.25h-9.5z");
}

</style>
