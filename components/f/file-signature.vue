<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="givluni7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-signature" /></template>
<style>
.givluni7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2L8 2C5.79086 2 4 3.79086 4 6L4 18C4 20.2091 5.79086 22 8 22L16 22C18.2091 22 20 20.2091 20 18L20 8L14 2ZM14 2L14 5C14 6.65685 15.3431 8 17 8L20 8M8 13.7228C10.1818 13.2431 10.4242 11.324 10.6666 12.2835C10.9091 13.2431 11.3939 14.2026 12.1212 13.9627C12.8485 13.7228 13.0909 12.5234 13.5757 13.2431C14.0606 13.9627 15.2728 13.9627 16 13.9627M8 18L16 18");
}

</style>
