<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djp8cebks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d20-sharp" /></template>
<style>
.djp8cebks {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2.0023L21 6.7872L21 17.2128L12 21.9977L3 17.2128L3 6.7872ZM12 7L8 14L16 14ZM3.3978 7.0154L12 7L20.6022 7.0154M3.3978 7.0154L8 14L12 22L16 14L20.6022 7.0154");
}

</style>
