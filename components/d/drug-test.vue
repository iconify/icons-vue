<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umqjo557f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drug-test" /></template>
<style>
.umqjo557f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.25h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014h-.25V17q0 2.75-2.75 2.75T9.25 17V3.75H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q8.926 2.25 9 2.25m1.75 10.5V17q0 1.25 1.25 1.25T13.25 17v-4.25zm2.5-1.5h-2.5v-7.5h2.5z");
}

</style>
