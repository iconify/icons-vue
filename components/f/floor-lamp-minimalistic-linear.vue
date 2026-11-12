<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ick8o1b-y"/><path class="g40jultif"/><path class="g80rf7b8i"/><path class="tsu3ypo6o"/><path class="y6dum9mni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:floor-lamp-minimalistic-linear" /></template>
<style>
.g40jultif {
  d: path("M12 22V8");
}

.g80rf7b8i {
  d: path("M16.8475 4.98449C16.2992 6.71758 14.3369 8 12.0001 8C9.66331 8 7.70094 6.71758 7.15266 4.98449C6.98608 4.45792 7.4478 4 8.00009 4H16.0001C16.5524 4 17.0141 4.45792 16.8475 4.98449Z");
}

.ick8o1b-y {
  d: path("M9 22H15");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tsu3ypo6o {
  d: path("M15 4C15 2.89543 13.6569 2 12 2C10.3431 2 9 2.89543 9 4H15Z");
}

.y6dum9mni {
  d: path("M12 19V17.9368C12 16.6554 11.4101 15.4467 10.4035 14.6655L6.52181 11.8909M6.52181 11.8909C7.28701 10.8364 7.29602 9.44296 6.62898 8.39296C6.3242 7.9132 5.661 7.99543 5.31139 8.44298L2.7793 11.6844M2.7793 11.6844C2.4297 12.132 2.50541 12.8018 3.03895 12.9887C4.2398 13.4094 5.62367 13.0438 6.45481 11.9798C6.47776 11.9505 6.50009 11.9208 6.52181 11.8909M2.7793 11.6844C1.89216 10.9789 1.73982 9.6814 2.43904 8.7863C3.13826 7.8912 4.42425 7.73749 5.31139 8.44298");
}

</style>
