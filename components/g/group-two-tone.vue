<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jpfi-vwvh"/><path class="jaq1m1bdp"/><path clip-rule="evenodd" class="dpgk2uboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:group-two-tone" /></template>
<style>
.dpgk2uboc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 6.5C14 7.3285 13.3285 8 12.5 8C11.6715 8 11 7.3285 11 6.5C11 5.6715 11.6715 5 12.5 5C13.3285 5 14 5.6715 14 6.5ZM19 6.5C19 7.3285 18.3285 8 17.5 8C16.6715 8 16 7.3285 16 6.5C16 5.6715 16.6715 5 17.5 5C18.3285 5 19 5.6715 19 6.5ZM19 11.5C19 12.3285 18.3285 13 17.5 13C16.6715 13 16 12.3285 16 11.5C16 10.6715 16.6715 10 17.5 10C18.3285 10 19 10.6715 19 11.5Z");
  stroke: none;
}

.jaq1m1bdp {
  d: path("M15.8284 20C15.4046 21.1985 14.2714 22 13 22H5C3.3431 22 2 20.6569 2 19V11C2 9.7286 2.8015 8.5954 4 8.1716M11 16H19C20.6568 16 22 14.6568 22 13V5C22 3.3432 20.6568 2 19 2H11C9.3432 2 8 3.3432 8 5V13C8 14.6568 9.3432 16 11 16Z");
}

.jpfi-vwvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 17L19 17C21.2091 17 23 15.2091 23 13L23 5C23 2.7909 21.2091 1 19 1L11 1C8.7909 1 7 2.7909 7 5L7 13C7 15.2091 8.7909 17 11 17Z");
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
