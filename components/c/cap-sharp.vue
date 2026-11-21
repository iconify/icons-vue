<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhzmbymss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cap-sharp" /></template>
<style>
.vhzmbymss {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L12 13M2 15C5.1686 13.6797 8.5673 13 12 13C15.4327 13 18.8314 13.6797 22 15M22 15L22 12C22 7.0294 17.5228 3 12 3C6.4772 3 2 7.0294 2 12L2 15L2 19.5C2 20.3285 2.6716 21 3.5 21C3.7244 21 3.9459 20.9497 4.1483 20.8527C6.5991 19.6781 9.2822 19.0683 12 19.0683C14.7178 19.0683 17.4009 19.6781 19.8517 20.8527C20.0541 20.9497 20.2756 21 20.5 21C21.3284 21 22 20.3285 22 19.5Z");
}

</style>
