<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmr3y1zcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:awareness-ribbon-loop" /></template>
<style>
.bmr3y1zcw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.129 21.08l2.966-4.384l-2.216-3.276l-.015-.023Q7.25 10.815 7.25 7.5q0-2.165 1.345-3.684Q9.979 2.25 12 2.25t3.405 1.566Q16.75 5.335 16.75 7.5q0 3.315-1.614 5.897l-.015.023l-2.216 3.276l2.966 4.384q.042.061.07.129t.044.14q.015.073.015.147t-.014.146t-.041.141t-.069.13t-.093.114t-.113.094q-.123.084-.269.114t-.293.001q-.147-.028-.271-.11t-.208-.206L12 18.034L9.371 21.92q-.083.124-.208.206t-.271.11q-.146.029-.293-.001q-.146-.03-.269-.114q-.061-.041-.113-.094q-.052-.052-.093-.114t-.069-.13q-.027-.068-.041-.141T8 21.496t.015-.147q.015-.072.044-.14t.07-.129m5.742-8.489L12 15.357l-1.871-2.766Q8.75 10.378 8.75 7.5q0-3.75 3.25-3.75t3.25 3.75q0 2.878-1.379 5.091");
}

</style>
