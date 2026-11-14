<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_4s713_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:event-stream" /></template>
<style>
.m_4s713_a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2v.838Q14 3.169 14 4.75t-1.25 1.912v1.176Q14 8.169 14 9.75t-1.25 1.912v1.176Q14 13.169 14 14.75t-1.25 1.912v1.176Q14 18.169 14 19.75t-1.25 1.912V22q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 22v-.338Q10 21.331 10 19.75t1.25-1.912v-1.176Q10 16.331 10 14.75t1.25-1.912v-1.176Q10 11.331 10 9.75t1.25-1.912V6.662Q10 6.331 10 4.75t1.25-1.912V2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
