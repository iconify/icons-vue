<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvu3u2bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chutney-jar" /></template>
<style>
.cvu3u2bnz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.118 3q.524-1.5 3.382-1.5q1.33 0 2.304.531Q22 2.683 22 3.75Q22 6 18.5 6q-2.858 0-3.382-1.5H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.426 3 3.5 3zM7.5 6.75h9q2.25 0 2.25 2.25q0 1.276-.723 1.828q.467.327.892.753Q20.75 13.411 20.75 16t-1.831 4.419T14.5 22.25h-5q-2.589 0-4.419-1.831Q3.25 18.589 3.25 16t1.831-4.419q.425-.426.892-.753Q5.25 10.276 5.25 9q0-2.25 2.25-2.25");
}

</style>
