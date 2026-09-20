<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo--el8ej"/><path class="nivm83buf"/><path class="zueuhs0mc"/><path class="ky4omnbla"/><path class="vrzboac1q"/><path class="ipav-zhpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balance-sheet-duotone-regular" /></template>
<style>
.ipav-zhpr {
  d: path("M14.5 8.5v7");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.nivm83buf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vrzboac1q {
  d: path("M9.5 8.5v7");
}

.wo--el8ej {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zueuhs0mc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
