<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oanys0b_d"/><path class="rilpaib4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-operation-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oanys0b_d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L18.9972 4C20.3986 4 21.5864 4.7064 22.2925 5.7327C22.9986 6.7589 23.2339 8.1208 22.7331 9.4296L19.6717 17.4296C19.0793 18.9777 17.5934 20 15.9359 20L8.0641 20C6.4066 20 4.9207 18.9777 4.3283 17.4296L1.2669 9.4296C0.7661 8.1208 1.0014 6.7589 1.7075 5.7327C2.4136 4.7064 3.6014 4 5.0028 4Z");
  stroke: none;
}

.rilpaib4e {
  d: path("M5.0028 5L18.9972 5C21.1004 5 22.5507 7.1079 21.7991 9.0722L18.7377 17.0722C18.2934 18.2333 17.179 19 15.9359 19L8.0641 19C6.821 19 5.7066 18.2333 5.2623 17.0722L2.2009 9.0722C1.4493 7.1079 2.8996 5 5.0028 5Z");
}

</style>
