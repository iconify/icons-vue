<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bx4fqnbwk"/><path clip-rule="evenodd" class="hxhgz-blg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-plus-fill" /></template>
<style>
.bx4fqnbwk {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2H5C3.34315 2 2 3.34315 2 5V13C2 14.2714 2.8015 15.4046 4 15.8284");
}

.hxhgz-blg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 7L19 7C21.20914 7 23 8.79086 23 11L23 19C23 21.20914 21.20914 23 19 23L11 23C8.79086 23 7 21.20914 7 19L7 11C7 8.79086 8.79086 7 11 7ZM14 14L14 12C14 11.44772 14.44772 11 15 11C15.55228 11 16 11.44772 16 12L16 14L18 14C18.55228 14 19 14.44772 19 15C19 15.55228 18.55228 16 18 16L16 16L16 18C16 18.55228 15.55228 19 15 19C14.44772 19 14 18.55228 14 18L14 16L12 16C11.44772 16 11 15.55228 11 15C11 14.44772 11.44772 14 12 14Z");
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
