<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uozyktirx"/><path class="z5pzvvpts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uozyktirx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.4 9.2C19.4386 10.5848 20 12.269 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 12.269 4.5614 10.5848 5.6 9.2L10.4 2.8C10.7777 2.2965 11.3703 2 12 2C12.6297 2 13.2223 2.2965 13.5999 2.7999L18.4 9.2Z");
  stroke: none;
}

.z5pzvvpts {
  d: path("M17.6 9.8C18.5088 11.0117 19 12.4854 19 14C19 17.866 15.866 21 12 21C8.134 21 5 17.866 5 14C5 12.4854 5.4912 11.0117 6.4 9.8L11.2 3.4C11.3889 3.1482 11.6852 3 12 3C12.3148 3 12.6111 3.1482 12.8 3.4L17.6 9.8Z");
}

</style>
