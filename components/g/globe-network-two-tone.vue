<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnawx7bxc"/><path class="ea0b78lxl"/><path clip-rule="evenodd" class="uu8ahhb0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-network-two-tone" /></template>
<style>
.ea0b78lxl {
  d: path("M12 2C16.142 2 19.5 5.358 19.5 9.5M12 2C7.858 2 4.5 5.358 4.5 9.5M12 2C13.667 4.25 14.5 6.875 14.5 9.5M12 2C10.333 4.25 9.5 6.875 9.5 9.5M19.5 9.5C19.5 13.642 16.142 17 12 17M19.5 9.5H14.5M12 17C7.858 17 4.5 13.642 4.5 9.5M12 17C13.667 14.75 14.5 12.125 14.5 9.5M12 17C10.333 14.75 9.5 12.125 9.5 9.5M12 17V21.5M4.5 9.5H9.5M9.5 9.5H14.5M12 21.5H3M12 21.5H21");
}

.fnawx7bxc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.5 9.5C20.5 14.194 16.694 18 12 18C7.306 18 3.5 14.194 3.5 9.5C3.5 4.806 7.306 1 12 1C16.694 1 20.5 4.806 20.5 9.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uu8ahhb0m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 20C12.828 20 13.5 20.672 13.5 21.5C13.5 22.328 12.828 23 12 23C11.172 23 10.5 22.328 10.5 21.5C10.5 20.672 11.172 20 12 20Z");
  stroke: none;
}

</style>
