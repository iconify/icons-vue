<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g70whwsdk"/><path class="c5yb8bdcb"/><path class="pcr6xabis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-alert-duotone" /></template>
<style>
.c5yb8bdcb {
  d: path("M12 7V13");
}

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

.pcr6xabis {
  fill: currentColor;
  d: path("M13 17C13 17.55228 12.55228 18 12 18C11.44772 18 11 17.55228 11 17C11 16.44772 11.44772 16 12 16C12.55228 16 13 16.44772 13 17Z");
  stroke: none;
}

</style>
