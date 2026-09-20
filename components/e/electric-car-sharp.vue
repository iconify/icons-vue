<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrgjtbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:electric-car-sharp" /></template>
<style>
.wrgjtbbvc {
  fill: currentColor;
  d: path("M6 15v2H3V8l2.45-7h13.1L21 8v9h-3v-2zm-.2-9h12.4l-1.05-3H6.85zm1.7 6q.625 0 1.063-.437T9 10.5t-.437-1.062T7.5 9t-1.062.438T6 10.5t.438 1.063T7.5 12m9 0q.625 0 1.063-.437T18 10.5t-.437-1.062T16.5 9t-1.062.438T15 10.5t.438 1.063T16.5 12M13 23l-6-3h4v-2l6 3h-4z");
}

</style>
