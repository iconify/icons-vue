<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmjoq4l1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gadget-water-damage" /></template>
<style>
.kmjoq4l1a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h.75q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624T8.625 22.25h-.75q-2.123 0-3.624-1.501T2.75 17.125V6.875q0-2.123 1.501-3.624T7.875 1.75m10.694 4.762Q21.75 10.223 21.75 13q0 3.75-3.75 3.75T14.25 13q0-2.777 3.181-6.488q.048-.056.106-.102t.124-.079t.137-.053t.144-.026t.147.003t.144.032t.135.059t.12.085q.044.037.081.081M6.5 17.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H10q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T10 17.75z");
}

</style>
