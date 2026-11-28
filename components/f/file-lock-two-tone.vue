<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5lkws9yp"/><path class="q4wced5nt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-lock-two-tone" /></template>
<style>
.j5lkws9yp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8L21 10C21 10.5523 20.5523 11 20 11L13 11C11.3431 11 10 12.3431 10 14L10 22C10 22.5523 9.5523 23 9 23L8 23C5.2386 23 3 20.7614 3 18L3 6C3 3.2386 5.2386 1 8 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q4wced5nt {
  d: path("M14 2H8C5.79086 2 4 3.79086 4 6V18C4 20.2091 5.79086 22 8 22H9M14 2L20 8V10M14 2V5C14 6.65685 15.3431 8 17 8H20M14 18L19 18C19.5523 18 20 18.4477 20 19L20 21C20 21.5523 19.5523 22 19 22L14 22C13.4477 22 13 21.5523 13 21L13 19C13 18.4477 13.4477 18 14 18ZM14.5 18L14.5 16C14.5 14.8954 15.3954 14 16.5 14C17.6046 14 18.5 14.8954 18.5 16L18.5 18");
}

</style>
