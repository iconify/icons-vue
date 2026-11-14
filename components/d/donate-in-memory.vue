<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghtpg0b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donate-in-memory" /></template>
<style>
.ghtpg0b2j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 8.94q-2-.345-2-2.69q0-1.337 1.737-3.444q.285-.346.427-.525q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.065.052.117.117q.142.179.427.525Q14.75 4.913 14.75 6.25q0 2.345-2 2.69v.31h.5q1.036 0 1.768.732t.732 1.768v7.5q0 .541-.2 1h2.95q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.75 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.95q-.2-.459-.2-1v-7.5q0-2.5 2.5-2.5h.5z");
}

</style>
