<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d49g9m2na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:landmark" /></template>
<style>
.d49g9m2na {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.2797 7.0511C3.1085 7.1351 2.9999 7.3093 2.9999 7.5C2.9999 7.7761 3.2238 8 3.5 8L20.5 8C20.7762 8 21 7.7761 21 7.5C21 7.3093 20.8915 7.1351 20.7203 7.0511L12.881 3.2045C12.6068 3.0699 12.3054 2.9999 12 2.9999C11.6946 2.9999 11.3932 3.0699 11.119 3.2045L3.2797 7.0511ZM6 12L6 17M12 12L12 17M18 12L18 17M3 21L21 21");
}

</style>
