<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1zcaje6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-turn-up-right" /></template>
<style>
.l1zcaje6u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 18.25h-8q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.75 19t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q2.382 0 4.066-1.684T17.25 14V6.811l2.72 2.719q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243T21.25 9t-.057-.287t-.163-.243l-4-4q-.105-.106-.243-.163T16.5 4.25t-.285.056t-.242.16l-.003.004h-.001l-3.999 4q-.053.052-.094.113t-.069.13t-.043.141T11.75 9t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.72-2.719V14q0 1.76-1.245 3.005T11.5 18.25");
}

</style>
