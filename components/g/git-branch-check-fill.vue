<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f0wfasbtv"/><path clip-rule="evenodd" class="tdhf2obdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-check-fill" /></template>
<style>
.f0wfasbtv {
  d: path("M6 21V9C6.16667 12 8.2 18 15 18M15 6L17 8L21 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tdhf2obdy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.8284 8.8284C9.5512 8.1057 10 7.1043 10 6C10 3.7909 8.2091 2 6 2C3.7909 2 2 3.7909 2 6C2 8.2091 3.7909 10 6 10C7.1043 10 8.1057 9.5512 8.8284 8.8284ZM20.8284 20.8284C21.5512 20.1057 22 19.1043 22 18C22 15.7908 20.2092 14 18 14C15.7908 14 14 15.7908 14 18C14 20.2092 15.7908 22 18 22C19.1043 22 20.1057 21.5512 20.8284 20.8284Z");
  stroke: none;
}

</style>
