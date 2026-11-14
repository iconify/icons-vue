<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykmuu1jvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-coin" /></template>
<style>
.ykmuu1jvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.47 21.03l-8.25-8.25Q.993 10.553 2.097 7.055Q3.299 3.25 7.5 3.25q2.744 0 4.5 2.186q1.756-2.186 4.5-2.186q4.201 0 5.403 3.805q1.104 3.498-1.123 5.725l-.4.401Q19.727 13 19 13h-2q-2.071 0-3.536 1.464Q12 15.929 12 18q0 1.542.812 2.748l-.282.282q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906m-5.144-.546q.114-.234.348-.348z");
}

</style>
