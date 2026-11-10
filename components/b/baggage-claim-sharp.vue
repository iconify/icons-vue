<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvs572bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baggage-claim-sharp" /></template>
<style>
.lvs572bkb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 17H23M4 17V12C4 7.582 7.582 4 12 4M12 4C16.418 4 20 7.582 20 12V17M12 4V1M8 17V12H10M10 12V8H14V12M10 12H14M14 12H16V17M18 22C16.895 22 16 21.105 16 20C16 18.895 16.895 18 18 18C19.105 18 20 18.895 20 20C20 21.105 19.105 22 18 22ZM6 22C4.895 22 4 21.105 4 20C4 18.895 4.895 18 6 18C7.105 18 8 18.895 8 20C8 21.105 7.105 22 6 22Z");
}

</style>
