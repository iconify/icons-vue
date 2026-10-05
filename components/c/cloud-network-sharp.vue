<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9flnybrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-network-sharp" /></template>
<style>
.u9flnybrh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 14.5C4.567 14.5 3 12.933 3 11C3 9.067 4.567 7.5 6.5 7.5C6.5 4.4624 8.9624 2 12 2C15.0376 2 17.5 4.4624 17.5 7.5C19.433 7.5 21 9.067 21 11C21 12.933 19.433 14.5 17.5 14.5ZM12 14.5L12 18L12 19M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20ZM5 20L6 20L10 20M14 20L18 20L19 20");
}

</style>
