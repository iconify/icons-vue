<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox6baccdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:daily-mix" /></template>
<style>
.ox6baccdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 14.516V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T15.5 3v14.5q0 1.689-1.357 2.865Q12.833 21.5 11 21.5t-3.143-1.135Q6.5 19.189 6.5 17.5t1.357-2.865Q9.167 13.5 11 13.5q1.734 0 3 1.016");
}

</style>
