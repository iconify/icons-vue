<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlc5azb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balance-training" /></template>
<style>
.vlc5azb-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.759 9.707q-1.955.416-1.541 2.372q.172.81.868 1.262q.695.451 1.505.279l2.005-.427Q5.25 14.943 5.25 17.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T6 18h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.796-1.977-4.773q-.686-.686-1.471-1.134l4.939-1.05q1.955-.416 1.541-2.372q-.172-.81-.868-1.262q-.695-.451-1.505-.279z");
}

</style>
