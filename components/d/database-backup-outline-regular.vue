<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iaozfqbuj"/><path class="l01wrb87q"/><path class="zpdz8rbaf"/><path class="j-8za4m4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:database-backup-outline-regular" /></template>
<style>
.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.j-8za4m4i {
  d: path("M11.5 13 9 15.5l2.5 2.5");
}

.l01wrb87q {
  d: path("M7 10.5h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zpdz8rbaf {
  d: path("M9 15.5h6");
}

</style>
