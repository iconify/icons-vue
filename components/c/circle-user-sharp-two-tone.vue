<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e9ewmybae"/><path class="l-1ucdbni"/><path class="qj_qb5bhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-user-sharp-two-tone" /></template>
<style>
.e9ewmybae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l-1ucdbni {
  d: path("M12 2C17.5228 2 22 6.4771 22 12C22 17.5228 17.5228 22 12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2Z");
}

.qj_qb5bhh {
  fill: currentColor;
  d: path("M12 6C13.5188 6 15 7.4812 15 9C15 10.5188 13.5188 12 12 12C10.4812 12 9 10.5188 9 9C9 7.4812 10.4812 6 12 6ZM11 14L13 14C15.6654 14 17.8419 16.0856 18 18.7082C16.3499 20.1841 14.2138 21 12 21C9.7862 21 7.6501 20.1841 6 18.7082C6.1571 16.0856 8.3346 14 11 14Z");
  stroke: none;
}

</style>
