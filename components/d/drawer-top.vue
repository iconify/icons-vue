<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsckffyge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drawer-top" /></template>
<style>
.dsckffyge {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 2.75H6.875q-2.123 0-3.624 1.501T1.75 7.875v8.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-8.25q0-2.123-1.501-3.624T17.125 2.75zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V6q0 .75.75.75h4q.75 0 .75-.75V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V6q0 .932-.659 1.591T14 8.25h-4Q7.75 8.25 7.75 6V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
