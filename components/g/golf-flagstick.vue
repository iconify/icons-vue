<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6dmwfbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:golf-flagstick" /></template>
<style>
.f6dmwfbuk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 16.251V8.416q.759.288 1.585-.043l1.961-.783q1.416-.566 1.416-2.09t-1.416-2.089l-1.96-.784h-.001q-.826-.331-1.585-.043V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v13.819q-4.5.385-4.5 2.931q0 3 6.25 3t6.25-3t-6.25-3z");
}

</style>
