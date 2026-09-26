<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dk-seobxs"/><path class="qu5h3fbqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-duotone" /></template>
<style>
.dk-seobxs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.5281 10.646L7.6698 3.969C8.2379 3.3514 9.0386 3 9.8778 3L19 3C21.2091 3 23 4.7909 23 7L23 17C23 19.2091 21.2091 21 19 21L9.8778 21C9.0386 21 8.2379 20.6486 7.6698 20.031L1.5281 13.354C1.1885 12.9848 1 12.5016 1 12C1 11.4984 1.1885 11.0152 1.5281 10.646Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qu5h3fbqg {
  d: path("M11 9L17 15M17 9L11 15");
}

</style>
