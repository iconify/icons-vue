<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsnfo_b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flanged-wheel" /></template>
<style>
.nsnfo_b2g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10q0-3.417 2.416-5.834T12 1.75t5.834 2.416Q20.25 6.583 20.25 10t-2.416 5.834q-.513.512-1.07.916h3.111q.984 0 1.679.696q.696.695.696 1.679t-.696 1.679q-.695.696-1.679.696H4.125q-2.375 0-2.375-2.375t2.375-2.375h3.111q-.557-.404-1.07-.916Q3.75 13.417 3.75 10m2.75 0q0-2.278 1.611-3.889T12 4.5t3.889 1.611T17.5 10t-1.611 3.889T12 15.5t-3.889-1.611T6.5 10");
}

</style>
