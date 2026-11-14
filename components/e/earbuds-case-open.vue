<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvht_dbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:earbuds-case-open" /></template>
<style>
.fvht_dbyp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.145 4.474l11.818-2.083q2.708-.477 3.186 2.231q.197 1.122-.456 2.055q-.654.933-1.776 1.131L6.1 9.892q-1.122.197-2.055-.456q-.933-.654-1.131-1.776q-.477-2.708 2.231-3.186m7.422 7.776h-1.175q-.173-.566-.624-1.018Q10.036 10.5 9 10.5q-2.092 0-2.433 1.75H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v2.5q0 2.175 1.538 3.712Q6.325 20.75 8.5 20.75h7q2.175 0 3.712-1.538q1.538-1.537 1.538-3.712V13q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 12.25h-2.608q-.173-.566-.624-1.018Q16.036 10.5 15 10.5q-2.092 0-2.433 1.75m3.095 0H14.25Q14.5 12 15 12q.383 0 .662.25M9 12q.383 0 .662.25H8.25Q8.5 12 9 12");
}

</style>
