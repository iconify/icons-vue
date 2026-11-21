<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8sdh2a9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lasso-sharp" /></template>
<style>
.v8sdh2a9r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7.5C3 5.0147 6.5817 3 11 3C15.4183 3 19 5.0147 19 7.5C19 9.9853 15.4183 12 11 12C6.5817 12 3 9.9853 3 7.5ZM16.3089 10.9236L16.5 11C19 12 20 13.5 18.5 15.5C17 17.5 18.5 19.5 21 21L21.2929 21.2929");
}

</style>
