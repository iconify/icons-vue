<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpx7i6bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:border-none-sharp" /></template>
<style>
.tpx7i6bbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h.01M3 7.5h.01M3 12h.01M3 16.5h.01M3 21h.01M7.5 3h.01M7.5 21h.01M12 3h.01M12 21h.01M16.5 3h.01m-.01 18h.01M21 3h.01M21 7.5h.01M21 12h.01M21 16.5h.01M21 21h.01M7.5 12h.01M12 7.5h.01M12 12h.01M12 16.5h.01M16.5 12h.01");
}

</style>
