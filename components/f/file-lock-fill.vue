<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="x7vvfbbim"/><path class="inqokcp_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-lock-fill" /></template>
<style>
.inqokcp_m {
  d: path("M14 18L19 18C19.5523 18 20 18.4477 20 19L20 21C20 21.5523 19.5523 22 19 22L14 22C13.4477 22 13 21.5523 13 21L13 19C13 18.4477 13.4477 18 14 18ZM14.5 18L14.5 16C14.5 14.8954 15.3954 14 16.5 14C17.6046 14 18.5 14.8954 18.5 16L18.5 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x7vvfbbim {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8L21 10C21 10.5523 20.5523 11 20 11L13 11C11.3431 11 10 12.3431 10 14L10 22C10 22.5523 9.5523 23 9 23L8 23C5.2386 23 3 20.7614 3 18L3 6C3 3.2386 5.2386 1 8 1ZM14 5C14 6.6568 15.3431 8 17 8L18.5858 8L14 3.4142Z");
  stroke: none;
}

</style>
