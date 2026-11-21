<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ow8lo6bov"/><path class="pv0brnjlu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-check-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow8lo6bov {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.6436 14.9423C2.0203 13.4781 1 11.3582 1 9C1 4.5817 4.5817 1 9 1C11.3582 1 13.4781 2.0203 14.9423 3.6436L13.5608 5.0251C9.1473 5.6562 5.6562 9.1473 5.0251 13.5608Z");
  stroke: none;
}

.pv0brnjlu {
  d: path("M4.3432 14.2427L4.0503 13.9498C2.7835 12.683 2 10.933 2 9C2 5.134 5.134 2 9 2C10.933 2 12.683 2.7835 13.9498 4.0503L14.2427 4.3432M12.2071 14.7071L12.5 15L14.5 17L17.5 14L17.7929 13.7071M22 15C22 18.866 18.866 22 15 22C11.134 22 8 18.866 8 15C8 11.134 11.134 8 15 8C18.866 8 22 11.134 22 15Z");
}

</style>
