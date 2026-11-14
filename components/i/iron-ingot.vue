<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it0enobvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:iron-ingot" /></template>
<style>
.it0enobvr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.09 18.25h11.82q1.713 0 2.725-1.383q1.011-1.383.492-3.015l-1.83-5.75q-.749-2.352-3.216-2.352H7.919q-2.467 0-3.216 2.352l-1.83 5.75q-.519 1.632.492 3.015T6.09 18.25m10.41-8q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.75 11t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
