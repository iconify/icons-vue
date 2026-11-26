<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dt6d0bc3q"/><path clip-rule="evenodd" class="t3xkukboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cupcake" /></template>
<style>
.dt6d0bc3q {
  d: path("M12 9H7C4.7909 9 3 10.7909 3 13C3 13.5523 3.4477 14 4 14H5M12 9H17C19.2091 9 21 10.7909 21 13C21 13.5523 20.5523 14 20 14H19M12 9V6M19 14H15M19 14L17.284 20.8638C17.1171 21.5315 16.5171 22 15.8288 22H14M15 14H9M15 14L14 22M9 14H5M9 14L10 22M5 14L6.716 20.8638C6.8829 21.5315 7.4829 22 8.1712 22H10M10 22H14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t3xkukboo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 2C13 2.5523 12.5523 3 12 3C11.4477 3 11 2.5523 11 2C11 1.4477 11.4477 1 12 1C12.5523 1 13 1.4477 13 2Z");
  stroke: none;
}

</style>
