<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pezpn2bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-up-short" /></template>
<style>
.pezpn2bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.7071 3.2929L21.7071 12.2929C21.9931 12.5789 22.0787 13.009 21.9239 13.3827C21.7691 13.7564 21.4045 14 21 14L18 14C17.4477 14 17 14.4477 17 15L17 20C17 20.5523 16.5523 21 16 21L8 21C7.4477 21 7 20.5523 7 20L7 15C7 14.4477 6.5523 14 6 14L3 14C2.5955 14 2.2309 13.7564 2.0761 13.3827C1.9213 13.009 2.0069 12.5789 2.2929 12.2929L11.2929 3.2929C11.6834 2.9024 12.3166 2.9024 12.7071 3.2929Z");
}

</style>
