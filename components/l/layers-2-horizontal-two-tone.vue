<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngw8d2bbp"/><path class="b5p3k2bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-2-horizontal-two-tone" /></template>
<style>
.b5p3k2bbg {
  d: path("M12 9.76L8.418 2.562C8.045 1.813 6.955 1.813 6.582 2.562L2.103 11.562C1.966 11.838 1.966 12.162 2.103 12.438L6.582 21.438C6.955 22.187 8.045 22.187 8.418 21.438L12 14.24M12 14.24L11.103 12.438C10.966 12.162 10.966 11.838 11.103 11.562L12 9.76L15.582 2.562C15.955 1.813 17.045 1.813 17.418 2.562L21.897 11.562C22.034 11.838 22.034 12.162 21.897 12.438L17.418 21.438C17.045 22.187 15.955 22.187 15.582 21.438L12 14.24Z");
}

.ngw8d2bbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.761 1.981C6.561 0.63 8.595 0.675 9.312 2.116L12 7.515L14.687 2.116L14.761 1.981C15.561 0.63 17.595 0.675 18.312 2.116L22.792 11.116C23.069 11.673 23.069 12.327 22.792 12.884L18.312 21.884C17.595 23.325 15.561 23.37 14.761 22.019L14.687 21.884L12 16.484L9.312 21.884C8.595 23.325 6.561 23.37 5.761 22.019L5.687 21.884L1.208 12.884C0.931 12.327 0.931 11.673 1.208 11.116L5.687 2.116L5.761 1.981Z");
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
