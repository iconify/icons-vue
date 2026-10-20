<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e85d4k35i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cone" /></template>
<style>
.e85d4k35i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.106 18.5133L11.0842 2.5984C11.434 1.8005 12.566 1.8005 12.9158 2.5984L19.894 18.5133M20 19C20 20.6569 16.4183 22 12 22C7.5817 22 4 20.6569 4 19C4 17.3431 7.5817 16 12 16C16.4183 16 20 17.3431 20 19Z");
}

</style>
