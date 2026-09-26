<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rdaefybbb"/><path class="yj0rwwbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-down-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rdaefybbb {
  stroke-opacity: 0.4;
  d: path("M4 11.1093L4 6C4 3.7909 5.7909 2 8 2L16 2C18.2091 2 20 3.7909 20 6L20 11.1093");
}

.yj0rwwbzi {
  d: path("M12 21.2307L12 11.1093M6.5 16.17L11.6314 21.8359C11.8296 22.0547 12.1704 22.0547 12.3686 21.8359L17.5 16.17");
}

</style>
