<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwi80gb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drop-spindle" /></template>
<style>
.jwi80gb4p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 13.016v1.742q7 .153 7 3.242t-7 3.242v.258q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-.258q-7-.153-7-3.242t7-3.242v-1.742Q7.125 11.359 7.125 8.5t4.125-4.516V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.484q4.125 1.657 4.125 4.516t-4.125 4.516");
}

</style>
