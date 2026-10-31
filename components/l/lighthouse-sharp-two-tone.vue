<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yo2eetb1v"/><path class="abq1pezws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lighthouse-sharp-two-tone" /></template>
<style>
.abq1pezws {
  d: path("M9 9L9 5L12 2L15 5L15 9ZM9 5L15 5M6 9L18 9M9 9L7 22M15 9L17 22M8.3846 13L15.6154 13M7.6923 17.5L16.3077 17.5M3 22L21 22M22.5528 2.7236L19.4472 4.2764M19.4472 13.7236L22.5528 15.2764M20 9L23 9M1.4472 2.7236L4.5528 4.2764M4.5528 13.7236L1.4472 15.2764M4 9L1 9");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yo2eetb1v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 8.9235L17.9884 21.8479C17.9961 21.8983 18 21.9491 18 22C18 22.5523 17.5523 23 17 23L7 23C6.4477 23 6 22.5523 6 22C6 21.9491 6.0039 21.8983 6.0116 21.8479L8 8.9235L8 5C8 4.7348 8.1054 4.4804 8.2929 4.2929L11.2929 1.2929C11.4804 1.1054 11.7348 1 12 1C12.2652 1 12.5196 1.1054 12.7071 1.2929L15.7071 4.2929C15.8946 4.4804 16 4.7348 16 5L16 8.9235Z");
  stroke: none;
}

</style>
