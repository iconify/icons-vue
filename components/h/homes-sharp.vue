<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er1q5t82m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:homes-sharp" /></template>
<style>
.er1q5t82m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 21L7 13.4473L14 8L21 13.4473L21 21ZM3 15L3 14L3 6.8909L8 3L10.956 5.3003L11.3419 5.6006M12 21L12 16L16 16L16 21");
}

</style>
