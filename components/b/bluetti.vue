<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cuuwy51jy"/><path class="e26xfob8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluetti" /></template>
<style>
.cuuwy51jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.05 41.01l17-29.445h-34z");
}

.e26xfob8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.435 26.808l3.615 8.321l11.544-20.252l-8.923.372l-.557 7.3zm.761-11.356l-8.69-.575l4.938 7.064l4.512-1.622zm.76 4.867l4.158 2.23M24.05 41.01v-5.881M12.506 14.877L7.05 11.565m28.544 3.312l5.456-3.312");
}

</style>
