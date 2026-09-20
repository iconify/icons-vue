<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5ic9acln"/><path class="skjwr0c_z"/><path class="xtpdjx99u"/><path class="de8hz-_3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:colbert-outline-regular" /></template>
<style>
.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.de8hz-_3f {
  d: path("M15 10.5v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skjwr0c_z {
  d: path("M9 10.5v5");
}

.xtpdjx99u {
  d: path("M12 10.5v5");
}

</style>
