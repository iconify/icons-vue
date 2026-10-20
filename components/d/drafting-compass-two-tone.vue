<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bjnwdd0in"/><path class="z5k8eurhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:drafting-compass-two-tone" /></template>
<style>
.bjnwdd0in {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3C13.6569 3 15 4.3431 15 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z5k8eurhr {
  d: path("M12 2L12 4M11.1984 7.8323L5 22M12.8016 7.8323L19 22M14 6C14 7.1046 13.1046 8 12 8C10.8954 8 10 7.1046 10 6C10 4.8954 10.8954 4 12 4C13.1046 4 14 4.8954 14 6ZM21 13.9373C18.722 16.5203 15.444 18 12 18C8.556 18 5.278 16.5203 3 13.9373");
}

</style>
