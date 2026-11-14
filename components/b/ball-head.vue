<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okw8ceb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-head" /></template>
<style>
.okw8ceb7f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 1.75h11q2.25 0 2.25 2.25T17.5 6.25h-1.434q.18.157.353.331Q18.25 8.411 18.25 11t-1.831 4.419q-.873.874-1.919 1.331v4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.5 21.5v-4.75q-1.046-.457-1.919-1.331Q5.75 13.589 5.75 11t1.831-4.419q.173-.174.353-.331H6.5Q4.25 6.25 4.25 4T6.5 1.75m5.5 15.5q-.515 0-1-.072v3.572h2v-3.572q-.485.072-1 .072");
}

</style>
