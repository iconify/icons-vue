<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3hy8shht"/><path clip-rule="evenodd" class="h-kt_zbwt"/><path class="ivshutbkw"/><path clip-rule="evenodd" class="ykzngxbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-list-duotone" /></template>
<style>
.e3hy8shht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7C3 4.7909 4.7909 3 7 3L17 3C19.2091 3 21 4.7909 21 7L21 19C21 21.2091 19.2091 23 17 23L7 23C4.7909 23 3 21.2091 3 19L3 7Z");
  stroke: none;
}

.h-kt_zbwt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4C6 2.3431 7.3431 1 9 1L15 1C16.6569 1 18 2.3431 18 4L18 5C18 6.6569 16.6569 8 15 8L9 8C7.3431 8 6 6.6569 6 5L6 4ZM8 4L8 5C8 5.5523 8.4477 6 9 6L15 6C15.5523 6 16 5.5523 16 5L16 4C16 3.4477 15.5523 3 15 3L9 3C8.4477 3 8 3.4477 8 4Z");
  stroke: none;
}

.ivshutbkw {
  d: path("M12 13L16 13M12 17L16 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ykzngxbve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 13C9 13.5523 8.5523 14 8 14C7.4477 14 7 13.5523 7 13C7 12.4477 7.4477 12 8 12C8.5523 12 9 12.4477 9 13ZM9 17C9 17.5523 8.5523 18 8 18C7.4477 18 7 17.5523 7 17C7 16.4477 7.4477 16 8 16C8.5523 16 9 16.4477 9 17Z");
  stroke: none;
}

</style>
