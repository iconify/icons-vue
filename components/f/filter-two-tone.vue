<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kftuk7bvi"/><path class="b5kf5wb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-two-tone" /></template>
<style>
.b5kf5wb7v {
  d: path("M3.2903 4.7025C2.6666 4.0707 3.1142 3 4.002 3L19.998 3C20.8858 3 21.3334 4.0707 20.7097 4.7025L14.2883 11.2079C14.1036 11.3951 14 11.6474 14 11.9104L14 18.4997C14 18.8146 13.8516 19.1112 13.5996 19.3L11.5996 20.7985C10.9403 21.2925 10 20.822 10 19.9982L10 11.9104C10 11.6474 9.8964 11.3951 9.7117 11.2079L3.2903 4.7025C2.6666 4.0707 3.1142 3 4.002 3Z");
}

.kftuk7bvi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.5786 5.405C2.012 4.831 1.8457 3.9728 2.1567 3.2286C2.4678 2.4845 3.1954 2 4.002 2L19.998 2C20.8046 2 21.5322 2.4845 21.8433 3.2286C22.1543 3.9728 21.988 4.831 21.4214 5.405L15 11.9104L15 18.4997C15 19.1296 14.7033 19.7226 14.1992 20.1003L12.1992 21.5988C11.5931 22.0529 10.7825 22.1257 10.1051 21.7868C9.4278 21.448 9 20.7556 9 19.9982L9 11.9104Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
