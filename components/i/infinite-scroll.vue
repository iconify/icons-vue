<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k40vt-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infinite-scroll" /></template>
<style>
.k40vt-bva {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 10.728Q9.893 13.25 7.5 13.25q-1.553 0-2.652-1.098Q3.75 11.053 3.75 9.5q0-3.75 3.75-3.75q2.393 0 4.5 2.522q2.107-2.522 4.5-2.522q3.75 0 3.75 3.75q0 1.553-1.098 2.652q-1.099 1.098-2.652 1.098q-2.393 0-4.5-2.522m0 8.211L9.03 15.97q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113l3.5 3.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l3.5-3.5q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094z");
}

</style>
