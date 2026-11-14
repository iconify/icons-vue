<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lehgqwb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donate-button" /></template>
<style>
.lehgqwb0q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 4.75H9q-3.003 0-5.127 2.123T1.75 12t2.123 5.127Q5.997 19.25 9 19.25h6q3.003 0 5.127-2.123T22.25 12t-2.123-5.127Q18.003 4.75 15 4.75m-3.53 11.53l-3-3q-2.031-2.03 0-4.06q.841-.841 2.03-.841q.836 0 1.5.415q.664-.415 1.5-.415q1.189 0 2.03.841q2.031 2.03 0 4.06l-3 3q-.052.053-.113.094t-.13.069t-.141.043T12 16.5t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
