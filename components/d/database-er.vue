<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6sfebty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-er" /></template>
<style>
.ha6sfebty {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5q0-2.75 5.75-2.75T13.75 5v9q0 2.564-5 2.737v1.013h6.251q.062-3.25 3.374-3.25h.75q3.375 0 3.375 3.375v.75q0 1.398-.989 2.386q-.988.989-2.386.989h-.75q-1.398 0-2.386-.989q-.76-.759-.936-1.761H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.763q-5-.173-5-2.737zM8 15.25q4.25 0 4.25-1.25v-2.583q-.204.101-.436.194q-1.598.639-3.814.639q-2.813 0-4.25-.658V14q0 1.25 4.25 1.25m4.25-8.158Q10.813 7.75 8 7.75t-4.25-.658V9.5q0 1.25 4.25 1.25t4.25-1.25z");
}

</style>
