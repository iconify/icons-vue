<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a3bildhzo"/><path class="nfxanex5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-line-duotone" /></template>
<style>
.a3bildhzo {
  d: path("M19 14H22M5 14H2M14.2905 3.62571L17 2M9.70947 3.62569L6.99998 2M17.8003 18.9202L20.5002 20.0001M17.7798 9.08789L20.4999 7.99984M6.19971 18.9202L3.49987 20.0001M12 22V15M6.22021 9.08789L3.50018 7.99988");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nfxanex5e {
  d: path("M16.5 8.27065V7.5C16.5 5.01472 14.4853 3 12 3C9.51472 3 7.5 5.01472 7.5 7.5V8.27065M19 11.9375V15C19 18.866 15.866 22 12 22C8.13401 22 5 18.866 5 15V11.9375C5 9.76288 6.76288 8 8.9375 8H15.0625C17.2371 8 19 9.76288 19 11.9375Z");
}

</style>
