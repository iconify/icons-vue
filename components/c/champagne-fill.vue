<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hcza5mbol"/><path class="r8xbe2guc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:champagne-fill" /></template>
<style>
.hcza5mbol {
  fill: currentColor;
  d: path("M12 1L15 1C16.1046 1 17 1.8954 17 3C17 3.2902 17.0248 3.5695 17.0675 3.8488C17.0752 3.8989 17.079 3.9494 17.079 4C17.079 4.5523 16.6313 5 16.079 5L12 5L7.921 5C7.3687 5 6.921 4.5523 6.921 4C6.921 3.9494 6.9248 3.8989 6.9325 3.8488C6.9752 3.5695 7 3.2902 7 3C7 1.8954 7.8954 1 9 1ZM6.442 11.7396C6.154 10.9028 6 9.9798 6 9C6 8.6104 6.0221 8.2424 6.0597 7.8931C6.1143 7.3851 6.543 7 7.0539 7L7.4503 7L12 7L16.5497 7L16.9461 7C17.457 7 17.8857 7.3851 17.9403 7.8931C17.9779 8.2424 18 8.6104 18 9C18 10.9577 17.3838 12.6948 16.313 13.9588C15.2373 15.2289 13.7153 16 12 16C10.2847 16 8.7627 15.2289 7.687 13.9588C7.1519 13.3272 6.7299 12.5762 6.442 11.7396Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r8xbe2guc {
  d: path("M12 15V22M8 22H16");
}

</style>
