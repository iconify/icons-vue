<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-uccli7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-asterisk" /></template>
<style>
.t-uccli7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H5C3.343 20 2 18.657 2 17V7M2 7C2 5.343 3.343 4 5 4H19C20.657 4 22 5.343 22 7M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M22 7V10M19 14V17M19 17V20M19 17L16.6 18.8M19 17L21.4 15.2M19 17L16.6 15.2M19 17L21.4 18.8");
}

</style>
