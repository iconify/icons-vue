<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1gm1rzab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-chamfer-two-tone" /></template>
<style>
.q1gm1rzab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L14.5858 3C14.851 3 15.1054 3.1054 15.2929 3.2929L20.7071 8.7071C20.8946 8.8946 21 9.149 21 9.4142L21 21");
}

</style>
