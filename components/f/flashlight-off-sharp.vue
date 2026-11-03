<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjvcqrbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight-off-sharp" /></template>
<style>
.zjvcqrbvd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12L12 12M8 8L2 8L2 16L9.7639 16C11.2344 16 12.6847 16.3424 14 17C15.2439 17.6219 16.6086 17.9619 17.997 17.997M17 7L17 12.3431M22 17.3431L22 6L18.2361 6C16.7656 6 15.3153 6.3424 14 7C13.6946 7.1527 13.382 7.2883 13.0635 7.4067L12.1262 7.7551M1.7071 1.7071L22.2929 22.2929");
}

</style>
