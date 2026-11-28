<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jb3959bwr"/><path class="uk-eumb3f"/><path clip-rule="evenodd" class="t99guct0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-user-two-tone" /></template>
<style>
.jb3959bwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C18.075 1 23 5.925 23 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t99guct0p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 9C15 10.657 13.657 12 12 12C10.343 12 9 10.657 9 9C9 7.343 10.343 6 12 6C13.657 6 15 7.343 15 9ZM13 14C15.665 14 17.842 16.086 18 18.708C16.35 20.184 14.214 21 12 21C9.786 21 7.65 20.184 6 18.708C6.157 16.086 8.335 14 11 14H13Z");
  stroke: none;
}

.uk-eumb3f {
  d: path("M12 2C17.523 2 22 6.477 22 12C22 17.523 17.523 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2Z");
}

</style>
