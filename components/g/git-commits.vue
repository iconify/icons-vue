<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-hwbcbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git-commits" /></template>
<style>
.dq-hwbcbv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 3.81q-2 .345-2 2.69t2 2.69v5.62q-2 .345-2 2.69t2 2.69V22q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.81q2-.345 2-2.69t-2-2.69V9.19q2-.345 2-2.69t-2-2.69V2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.25 12 1.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13q-.028.068-.043.141T11.25 2z");
}

</style>
