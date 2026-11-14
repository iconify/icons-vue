<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohf7apx9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:club-suit" /></template>
<style>
.ohf7apx9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.864 18.385q.305-.092.585-.215l-.664 2.104q-.022.071-.031.144q-.008.073-.001.147q.006.074.027.145t.055.136t.08.123t.103.105q.056.048.121.083t.135.058q.11.035.226.035h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.116-.035-.226l-.664-2.104q.28.123.585.215q1.865.566 3.589-.341q1.725-.907 2.316-2.764t-.293-3.594t-2.732-2.352q-.797-.266-1.576-.257q.293-.762.309-1.645q.037-1.993-1.36-3.415Q13.993 2.595 12 2.595T8.611 4.017t-1.36 3.415q.016.883.309 1.645q-.779-.009-1.576.257q-1.849.616-2.732 2.352q-.884 1.737-.293 3.594t2.316 2.764t3.589.341");
}

</style>
