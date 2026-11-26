<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v30atrbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glass-water-sharp" /></template>
<style>
.v30atrbiw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.0016 2L20.9983 2L18 22L6 22ZM3.7441 6.9499C6.1187 6.0003 9.5425 6.017 12 7C14.4525 7.981 17.8674 7.9996 20.2413 7.0559");
}

</style>
