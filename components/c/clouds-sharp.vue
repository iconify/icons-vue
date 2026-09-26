<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3990bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clouds-sharp" /></template>
<style>
.iu3990bny {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 20L14 20C15.6569 20 17 18.6569 17 17C17 15.3431 15.6569 14 14 14C14 11.5147 11.9853 9.5 9.5 9.5C7.0147 9.5 5 11.5147 5 14C3.3431 14 2 15.3431 2 17C2 18.6569 3.3431 20 5 20ZM17.8989 12L19.5 12C20.8807 12 22 10.8807 22 9.5C22 8.1193 20.8807 7 19.5 7C19.5 5.3431 18.1569 4 16.5 4C15.0285 4 13.7742 5.0673 13.5387 6.5198L13.3786 7.5069");
}

</style>
