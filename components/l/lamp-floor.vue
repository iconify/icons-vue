<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-m5oib3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-floor" /></template>
<style>
.q-m5oib3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12V22M9 22H15M9.712 2.503C9.8901 2.192 10.2213 2 10.5799 2H13.4201C13.7787 2 14.1099 2.192 14.288 2.503L18.8664 10.503C19.248 11.17 18.7666 12 17.9985 12H6.0015C5.2334 12 4.752 11.17 5.1336 10.503L9.712 2.503Z");
}

</style>
