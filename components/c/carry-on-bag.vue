<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsjytabeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carry-on-bag" /></template>
<style>
.jsjytabeg {
  fill: currentColor;
  d: path("M14.938 21.063Q14.5 20.625 14.5 20t.438-1.062T16 18.5t1.063.438T17.5 20t-.437 1.063T16 21.5t-1.062-.437M8 21q-.825 0-1.412-.587T6 19V9q0-.825.588-1.412T8 7h1v14zm2.5 0V7H14V4q-.825 0-1.412-.587T12 2h4v15q-1.25 0-2.125.875T13 20q0 .275.038.513t.137.487z");
}

</style>
