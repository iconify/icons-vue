<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naxq02buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:buy-two-get-one" /></template>
<style>
.naxq02buf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.188 2.849q-.733.336-1.188.939q-.455-.603-1.188-.939q-.939-.43-1.714.011q-.848.483-.848 1.64q0 .711.458 1.283Q6.75 6.038 6.75 8.25v4q0 .564.127 1H4.25q-1.036 0-1.768.732T1.75 15.75v4q0 1.036.732 1.768t1.768.732h5.5q1.036 0 1.768-.732q.304-.305.482-.661q.178.356.482.661q.732.732 1.768.732h5.5q1.036 0 1.768-.732t.732-1.768v-4q0-1.036-.732-1.768t-1.768-.732h-2.627q.127-.436.127-1v-4q0-2.212-1.958-2.467q.458-.572.458-1.283q0-1.157-.848-1.64q-.775-.441-1.714-.011M11.25 7.178q.377.072.75.072t.75-.072V14q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 14z");
}

</style>
