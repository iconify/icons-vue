<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ei-1i_lvh"/><path class="idoyxbc8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glass-water-two-tone" /></template>
<style>
.ei-1i_lvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.3849 11.8915L2.0248 3.3132C1.8324 2.0988 2.7707 1 4.0002 1L19.9998 1C21.2292 1 22.1677 2.0988 21.9751 3.3132L19.2551 20.4698C19.0241 21.9271 17.7676 23 16.2921 23L7.7079 23C6.2324 23 4.9759 21.9271 4.7449 20.4698Z");
  stroke: none;
}

.idoyxbc8j {
  d: path("M4.0002 2H19.9998C20.6145 2 21.0837 2.5494 20.9874 3.1566L18.2674 20.3132C18.1134 21.2847 17.2758 22 16.2921 22H7.7079C6.7242 22 5.8866 21.2847 5.7326 20.3132L3.0125 3.1566C2.9163 2.5494 3.3855 2 4.0002 2ZM3.6219 7C6 6 9.5 6 12 7C14.5 8 18 8 20.3781 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
