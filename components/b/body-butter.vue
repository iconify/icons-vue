<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrwo_9kin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:body-butter" /></template>
<style>
.yrwo_9kin {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.499 8.756q5.65.139 6.193 3.494H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5q0 3.25-3.25 3.25H6q-3.25 0-3.25-3.25v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.808q.516-3.186 5.636-3.472q-.31-1.374.394-2.693q1.016-1.904 3.539-2.325q.073-.012.146-.01q.074.003.146.019q.072.017.139.047q.068.031.128.074t.111.096t.089.117t.066.132q.026.069.038.142q.024.147-.009.292q-.034.146-.121.267q-.086.121-.213.2t-.274.104q-1.794.299-2.461 1.55q-.507.951-.163 1.966M6.864 12.25q.659-2 5.136-2t5.136 2z");
}

</style>
