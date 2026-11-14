<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmifnpy1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angle-gauge" /></template>
<style>
.nmifnpy1w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.273 16.738l2.436-4.15q2.736 1.87 3.011 5.162H6.892q-.172-.563-.619-1.012m3.197-5.447l3.177-5.411q.037-.064.061-.134q.025-.07.035-.143t.006-.147q-.005-.073-.023-.145q-.019-.071-.051-.138q-.032-.066-.077-.125q-.044-.059-.099-.108t-.119-.087q-.129-.075-.277-.096q-.148-.02-.292.017t-.263.128q-.119.09-.195.218L4.946 16.036Q4.731 16 4.5 16Q2 16 2 18.5T4.5 21q1.036 0 1.768-.732q.451-.452.624-1.018H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-8.275q-.283-4.15-3.755-6.459");
}

</style>
