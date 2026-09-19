<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fns19nb9v"/><path class="x1zz7jcwl"/><path class="l57d17i0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bkash" /></template>
<style>
.fns19nb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.981 8.632s-4.163 14.704-3.809 14.704s16.476 2.923 16.476 2.923Z");
}

.l57d17i0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.387 33.522l.354 1.905l-8.016 6.421l5.447-18.512m16.476 2.923l-.531 2.879l-12.269 3.64M8.455 8.997H5L16.044 19.15");
}

.x1zz7jcwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.981 8.632L6.329 6.152l12.843 17.184l2.215 10.186l14.261-7.263l3.72-8.814l-8.975 1.501m7.536 1.909H43l-3.632-3.41");
}

</style>
