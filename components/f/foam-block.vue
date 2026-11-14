<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thw94yvme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:foam-block" /></template>
<style>
.thw94yvme {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.52 9.424q-.026.021-.05.045l5-4.999q.024-.024.05-.046q3.461-2.885 7.187-.018q2.774 2.133 5.313.018q-.026.022-.05.046l-4.976 4.975q-2.527 2.084-5.287-.039q-3.726-2.867-7.187.018m13.73.887V21q0 .149-.057.287t-.163.243l5-5q.106-.105.163-.243T21.25 16V5q0 .149-.057.287t-.163.243zM2.25 21V10q0 .132.045.255q.045.124.129.225q.095.115.227.184q.133.069.281.083t.291-.031t.257-.14q2.539-2.115 5.313.018q3.068 2.361 5.957.821V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21");
}

</style>
