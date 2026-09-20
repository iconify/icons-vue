<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i3-g-7uyo"/><path class="eog6q6bsf"/><path class="zc6ogu6ot"/><path class="vqp2oy3do"/><path class="v9l_7xbhq"/><path class="nbib5l08z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:book-open-duotone-regular" /></template>
<style>
.eog6q6bsf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i3-g-7uyo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nbib5l08z {
  d: path("M12 7v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v9l_7xbhq {
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
}

.vqp2oy3do {
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
}

.zc6ogu6ot {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
