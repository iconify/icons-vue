<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i25n86xeu"/><path class="nv7y8vb6a"/><path class="o04wxjn8k"/><path class="tcce8sb5i"/><path class="uw5kuce7r"/><path class="j41x8568l"/><path class="zdse1fb0u"/><path class="cfq8fpb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-left-obj-duotone-regular" /></template>
<style>
.cfq8fpb9k {
  d: path("M5.5 17H12");
}

.i25n86xeu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j41x8568l {
  d: path("M5.5 7H15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nv7y8vb6a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 7H15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o04wxjn8k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 12H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tcce8sb5i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 17H12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.zdse1fb0u {
  d: path("M5.5 12H19");
}

</style>
