<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gajhjacck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cable-puller" /></template>
<style>
.gajhjacck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 8q0-2.589 1.831-4.419Q6.911 1.75 9.5 1.75H19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146V17q0 3.25-3.25 3.25T13.25 17v-1.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V17q0 1.75 1.75 1.75T18.25 17V3.25h-4.684q.18.157.353.331Q15.75 5.411 15.75 8t-1.831 4.419T9.5 14.25t-4.419-1.831Q3.25 10.589 3.25 8M7 8q0-2.5 2.5-2.5T12 8t-2.5 2.5T7 8");
}

</style>
