<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj-n5mbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-big-down-line" /></template>
<style>
.rj-n5mbji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 4.25h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q15.074 2.75 15 2.75H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T9 4.25m.923 15.733l-4.039-4.039q-.747-.745-.343-1.72t1.46-.974q1.249 0 1.249-1.25v-1.812q0-2.938 2.938-2.938h1.625q2.937.001 2.937 2.938V12q0 1.25 1.25 1.25q1.055-.001 1.459.974t-.343 1.721l-4.039 4.038q-2.077 2.077-4.154 0");
}

</style>
