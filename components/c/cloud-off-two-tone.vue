<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzsiy7bby"/><path class="b1u2suopy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-off-two-tone" /></template>
<style>
.b1u2suopy {
  d: path("M7.2868 7.2868C6.4809 8.3082 6 9.5979 6 11C3.7909 11 2 12.7909 2 15C2 17.2091 3.7909 19 6 19H18C18.309 19 18.6098 18.965 18.8986 18.8986M2 2L22 22");
}

.mzsiy7bby {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.5753 6.5753C5.7762 7.5539 5.2343 8.7574 5.0595 10.0893C2.5271 10.5743 0.7788 12.9055 1.0224 15.4724C1.266 18.0393 3.4216 20 6 20H18C18.5962 20 19.1697 19.8952 19.7023 19.7023L6.5753 6.5753ZM21.1192 16.8766C21.3675 17.125 21.728 17.2248 22.0687 17.1397C22.4094 17.0545 22.6805 16.7969 22.7829 16.4609C22.8791 16.1442 22.9452 15.8136 22.9776 15.4724C23.2212 12.9055 21.4729 10.5743 18.9405 10.0893C18.4833 6.6052 15.5139 4 12 4C11.514 4 11.0384 4.0498 10.5784 4.145C10.2184 4.2194 9.9284 4.4853 9.823 4.8374C9.7176 5.1895 9.814 5.571 10.0739 5.8309L21.1192 16.8766Z");
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
