<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1h1ms6ek"/><path class="tro3gkdum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d4-two-tone" /></template>
<style>
.h1h1ms6ek {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22L19.1943 22C20.6788 22 21.8764 21.168 22.5045 20.0393C23.132 18.9116 23.2122 17.4529 22.4623 16.1724L15.268 3.8869C14.5353 2.6357 13.2661 2.0001 12 2.0001C10.7339 2.0001 9.4647 2.6357 8.732 3.8869L1.5377 16.1724C0.7878 17.4529 0.868 18.9116 1.4955 20.0393C2.1236 21.168 3.3212 22 4.8057 22Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tro3gkdum {
  d: path("M14.4051 4.3922C13.3181 2.536 10.6819 2.536 9.5949 4.3922L2.4006 16.6777C1.2854 18.5822 2.6307 21 4.8057 21L19.1943 21C21.3693 21 22.7146 18.5822 21.5994 16.6777L14.4051 4.3922ZM12 3L12 14M2.3693 19.553L12 14L21.6307 19.553");
}

</style>
