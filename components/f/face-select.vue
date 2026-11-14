<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5aki5bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-select" /></template>
<style>
.x5aki5bmi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.53 20.53q-.099.099-.226.156q-.128.056-.268.063L14 20.75H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 20V10q0-.149.057-.287t.163-.243v-.001l6-5.999q.105-.106.243-.163T10 3.25h10q.149 0 .287.057t.243.163q.106.105.163.243T20.75 4v10q0 .149-.057.287t-.163.243zM10.311 4.75l-4.5 4.5h7.878l4.5-4.5zm4.439 5.561v7.878l4.5-4.5V5.811z");
}

</style>
