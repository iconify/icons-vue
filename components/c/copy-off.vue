<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_1zchuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-off" /></template>
<style>
.yn_1zchuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.8787 2.8787C2.3358 3.4216 2 4.1716 2 5L2 13C2 14.2714 2.8015 15.4046 4 15.8284M15.8284 4C15.4046 2.8015 14.2714 2 13 2L7.6569 2M21.1213 21.1213C20.5784 21.6642 19.8284 22 19 22L11 22C9.3432 22 8 20.6568 8 19L8 11C8 10.1716 8.3358 9.4216 8.8787 8.8787M13.6569 8L19 8C20.6568 8 22 9.3432 22 11L22 16.3431M2 2L22 22");
}

</style>
