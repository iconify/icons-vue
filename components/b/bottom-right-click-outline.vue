<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1i4zoqyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-right-click-outline" /></template>
<style>
.k1i4zoqyo {
  fill: currentColor;
  d: path("M3.98 20v-1h14.405q.269 0 .442-.173t.173-.442V4.019h1v14.366q0 .67-.472 1.143q-.472.472-1.143.472zm9.954-3.934Q13.5 15.633 13.5 15t.434-1.066T15 13.5t1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434t-1.066-.434M6 12v-1h4.292l-6.08-6.1l.688-.689l6.1 6.081V6h1v6z");
}

</style>
