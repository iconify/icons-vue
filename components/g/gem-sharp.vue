<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btb412y4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gem-sharp" /></template>
<style>
.btb412y4j {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 3L16.5 3L21.9989 10.4793L12 20.9984L2.0011 10.4793ZM2.048 10.4164L21.952 10.4164M7.4845 3.0179L12 10.4164L16.5155 3.0179");
}

</style>
