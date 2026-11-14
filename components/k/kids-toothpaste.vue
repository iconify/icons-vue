<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqnd4kbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kids-toothpaste" /></template>
<style>
.mqnd4kbsl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.375 3.077q-1.263 0-2.155.893q-.118.118-.175.275q-.836.096-1.454.715l-.707.707q-.733.732-.733 1.768q0 .104.008.206q-.447.107-.914.434l-6.254 4.391q-.692.486-.495 1.309q.196.822 1.033.942l.188.027q.525.075.63.595l.126.631q.294 1.47 1.764 1.764l.631.126q.521.104.595.627l.027.191q.12.837.942 1.033q.823.197 1.309-.495l4.391-6.254q.276-.393.395-.773q1.007.14 2.013-.865l.708-.708q.733-.732.733-1.767q0-.483-.16-.9q.602-.788.602-1.824q0-1.263-.893-2.155q-.892-.893-2.155-.893m1.492 3.622L17.126 4.96q-.155-.156-.324-.278q.265-.105.573-.105q.641 0 1.095.453q.834.835.397 1.669");
}

</style>
