<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svg8jzbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-trailer" /></template>
<style>
.svg8jzbzg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.804 16.5H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.011l-1.508.422q.008.166.008.339q0 4-4 4t-4-4t4-4q2.952 0 3.725 2.178l1.775-.497V10.5q0-2.278 1.611-3.889T16.75 5t3.889 1.611T22.25 10.5v5.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.804q-.348 2.25-2.946 2.25t-2.946-2.25m-1.054-3.751V10.5q0-4 4-4q2 0 3 1t1 3V15h-1.054q-.348-2.25-2.946-2.25T13.804 15H12.75z");
}

</style>
