<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgxbicb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flower-heart" /></template>
<style>
.bgxbicb0g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.804 4.721Q2.972 9.3 11.25 13.942v2.418q-1.606-1.61-4.75-1.61q-.074 0-.147.015t-.141.042q-.068.029-.129.07q-.062.041-.114.093q-.052.053-.093.114t-.069.13q-.028.068-.043.14t-.014.147q0 .074.015.146q.853 4.268 5.485 4.579V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.274q4.632-.311 5.485-4.579q.015-.072.015-.146t-.014-.147q-.015-.072-.043-.14t-.069-.13t-.093-.114t-.114-.093q-.061-.041-.129-.07q-.068-.028-.141-.042t-.147-.015q-3.144 0-4.75 1.61v-2.418q8.278-4.642 6.446-9.221l-.011-.026Q18.21 2.5 15.438 2.5Q13.271 2.5 12 3.94Q10.729 2.5 8.563 2.5q-2.773 0-3.748 2.195z");
}

</style>
