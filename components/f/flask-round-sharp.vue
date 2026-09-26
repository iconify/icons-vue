<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw6mbk9pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-round-sharp" /></template>
<style>
.dw6mbk9pw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 2L14.5 2L14.5 8.4617C17.2101 9.4979 19 12.0986 19 15C19 18.866 15.866 22 12 22C8.134 22 5 18.866 5 15C5 12.0986 6.7899 9.4979 9.5 8.4617L9.5 2ZM7 2L17 2M5.0718 16L18.9282 16");
}

</style>
