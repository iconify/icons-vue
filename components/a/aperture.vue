<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn27yzsuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:aperture" /></template>
<style>
.vn27yzsuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2ZM16.3301 9.5L6.3588 3.7431M16.3301 14.5L16.3301 2.9861M12 17L21.9713 11.2431M7.6699 14.5L17.6412 20.2569M7.6699 9.5L7.6699 21.0139M12 7L2.0287 12.7569");
}

</style>
