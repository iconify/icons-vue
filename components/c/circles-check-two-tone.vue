<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bguanyoqk"/><path class="ageygvbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-check-two-tone" /></template>
<style>
.ageygvbdn {
  d: path("M4.0503 13.9498C2.7835 12.683 2 10.933 2 9C2 5.134 5.134 2 9 2C10.933 2 12.683 2.7835 13.9498 4.0503M12.5 15L14.5 17L17.5 14M22 15C22 18.866 18.866 22 15 22C11.134 22 8 18.866 8 15C8 11.134 11.134 8 15 8C18.866 8 22 11.134 22 15Z");
}

.bguanyoqk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.4973 14.807C1.9593 13.349 1 11.2865 1 9C1 4.5817 4.5817 1 9 1C11.2865 1 13.349 1.9593 14.807 3.4973C14.91 3.6566 14.9698 3.8465 14.9698 4.0503C14.9698 4.5129 14.6619 4.9035 14.2399 5.0285C9.3231 5.398 5.398 9.3231 5.0285 14.2399C4.9035 14.6619 4.5129 14.9698 4.0503 14.9698C3.8465 14.9698 3.6566 14.91 3.4973 14.807Z");
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
