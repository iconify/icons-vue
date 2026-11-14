<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idewspb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bag-charm" /></template>
<style>
.idewspb3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 4.5q0-3.25 4.25-3.25q1.69 0 2.911.872q1.339.957 1.339 2.378q0 1.768-1.258 2.575q.568.353 1.074.859Q17.75 9.618 17.75 12t-1.684 4.066q-.935.935-2.084 1.351q.768 1.308.768 4.083q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.775.768-4.083q-1.149-.416-2.084-1.351Q6.25 14.382 6.25 12t1.684-4.066q.506-.506 1.074-.859Q7.75 6.268 7.75 4.5");
}

</style>
