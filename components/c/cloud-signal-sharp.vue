<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnha1_1_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-signal-sharp" /></template>
<style>
.dnha1_1_h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.0956 9.032L18.1265 9.002C18.0845 9.0007 18.0423 9 18 9C18 5.6863 15.3137 3 12 3C8.6863 3 6 5.6863 6 9C3.7909 9 2 10.7909 2 13C2 15.2091 3.7909 17 6 17L11.127 17M14 22L14 17M18 22L18 13M22 22L22 9");
}

</style>
