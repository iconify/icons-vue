<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqfd5abor"/><path class="y4yko-5tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-degree-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqfd5abor {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2C9.6296 2 10.2219 2.3 10.5996 2.8L15.4004 9.2C16.4389 10.58 17 12.27 17 14C17 18.42 13.4183 22 9 22C4.5817 22 1 18.42 1 14C1 12.27 1.5611 10.58 2.5996 9.2L7.4004 2.8C7.7781 2.3 8.3704 2 9 2ZM20 2C21.6569 2 23 3.34 23 5C23 6.66 21.6569 8 20 8C18.3431 8 17 6.66 17 5C17 3.34 18.3431 2 20 2Z");
  stroke: none;
}

.y4yko-5tm {
  d: path("M16 14C16 12.49 15.5088 11.01 14.6 9.8L9.8 3.4C9.6111 3.15 9.3148 3 9 3C8.6852 3 8.3889 3.15 8.2 3.4L3.4 9.8C2.4912 11.01 2 12.49 2 14C2 17.87 5.134 21 9 21C12.866 21 16 17.87 16 14ZM18 5C18 6.1 18.8954 7 20 7C21.1046 7 22 6.1 22 5C22 3.9 21.1046 3 20 3C18.8954 3 18 3.9 18 5Z");
}

</style>
