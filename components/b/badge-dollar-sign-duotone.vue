<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g70whwsdk"/><path class="z15tx_4tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-dollar-sign-duotone" /></template>
<style>
.g70whwsdk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.3891 8.1109C22.4205 9.1424 23 10.5413 23 12C23 13.4587 22.4205 14.8576 21.3891 15.8891C21.3891 18.9267 18.9267 21.3891 15.8891 21.3891C14.8576 22.4205 13.4587 23 12 23C10.5413 23 9.1424 22.4205 8.1109 21.3891C5.0733 21.3891 2.6109 18.9267 2.6109 15.8891C1.5795 14.8576 1 13.4587 1 12C1 10.5413 1.5795 9.1424 2.6109 8.1109C2.6109 5.0733 5.0733 2.6109 8.1109 2.6109C9.1424 1.5795 10.5413 1 12 1C13.4587 1 14.8576 1.5795 15.8891 2.6109C18.9267 2.6109 21.3891 5.0733 21.3891 8.1109Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z15tx_4tv {
  d: path("M12 6L12 18M14.5 7L10.5 7C9.1193 7 8 8.1193 8 9.5C8 10.8807 9.1193 12 10.5 12L13.5 12C14.8807 12 16 13.1193 16 14.5C16 15.8807 14.8807 17 13.5 17L9.5 17");
}

</style>
