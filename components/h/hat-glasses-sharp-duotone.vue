<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rc4l1o1iu"/><path clip-rule="evenodd" class="laouckjiw"/><path class="hgkgp9enu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hat-glasses-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hgkgp9enu {
  d: path("M10 17C10 15.8954 10.8954 15 12 15C13.1046 15 14 15.8954 14 17");
}

.laouckjiw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 17C11 19.2091 9.2091 21 7 21C4.7909 21 3 19.2091 3 17C3 14.7909 4.7909 13 7 13C9.2091 13 11 14.7909 11 17ZM21 17C21 19.2091 19.2091 21 17 21C14.7909 21 13 19.2091 13 17C13 14.7909 14.7909 13 17 13C19.2091 13 21 14.7909 21 17Z");
  stroke: none;
}

.rc4l1o1iu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.2792 9L6.0513 3.6838C6.1874 3.2754 6.5696 3 7 3L10 3C10.2164 3 10.4269 3.0702 10.6 3.2L12 4.25L13.4 3.2C13.5731 3.0702 13.7836 3 14 3L17 3C17.4304 3 17.8126 3.2754 17.9487 3.6838L19.7208 9L23 9L23 11L1 11L1 9L4.2792 9Z");
  stroke: none;
}

</style>
