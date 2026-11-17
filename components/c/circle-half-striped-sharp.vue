<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vezu37bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-half-striped-sharp" /></template>
<style>
.vezu37bey {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2C6.477 2 2 6.4772 2 12C2 17.5228 6.477 22 12 22M12 2C15.272 2 18.176 3.5711 20.001 6M12 2V22M12 22C15.272 22 18.176 20.4289 20.001 18M20.001 6C20.874 7.1628 21.5 8.5222 21.8 10C21.931 10.6462 22 11.3151 22 12C22 12.6849 21.931 13.3538 21.8 14C21.5 15.4777 20.874 16.8372 20.001 18M20.001 18H12M21.8 14H12M21.8 10H12M20.001 6H12");
}

</style>
