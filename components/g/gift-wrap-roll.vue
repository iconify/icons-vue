<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upvtqyb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gift-wrap-roll" /></template>
<style>
.upvtqyb4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 2.75q-4 0-4 2.25v14.5q0 2.25 4 2.25q1.511 0 2.612-.508q.534-.247.862-.561Q12.178 21.75 14 21.75h3.75q2.998-.002 2.998-3t-2.997-3H16.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.249q1.499.001 1.499 1.5t-1.498 1.5H14q-1.546 0-2.75-1.073V5q0-1.101-1.388-1.742Q8.761 2.75 7.25 2.75m2.5 4.042V19.5q0 .75-2.5.75t-2.5-.75V6.912q.949.338 2.5.338q1.435 0 2.5-.458");
}

</style>
