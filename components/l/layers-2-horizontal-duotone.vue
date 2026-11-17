<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jxvc-gqli"/><path class="iluo0lukj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-2-horizontal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iluo0lukj {
  d: path("M5.761 1.982C6.561 0.63 8.595 0.675 9.313 2.116L10.664 4.831C10.801 5.11 10.8 5.437 10.661 5.716L8.417 10.226C7.861 11.344 7.861 12.657 8.417 13.775L10.663 18.289C10.8 18.568 10.799 18.895 10.66 19.174L9.313 21.884C8.595 23.325 6.561 23.37 5.761 22.019L5.688 21.884L1.208 12.884C0.931 12.327 0.931 11.673 1.208 11.116L5.688 2.116L5.761 1.982Z");
}

.jxvc-gqli {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.761 1.981C15.561 0.63 17.595 0.675 18.312 2.116L22.792 11.116C23.069 11.673 23.069 12.327 22.792 12.884L18.312 21.884C17.595 23.325 15.561 23.37 14.761 22.019L14.687 21.884L10.208 12.884C9.931 12.327 9.931 11.673 10.208 11.116L14.687 2.116L14.761 1.981Z");
}

</style>
