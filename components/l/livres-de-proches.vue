<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjx2_rb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:livres-de-proches" /></template>
<style>
.cjx2_rb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.676c-1.47-3.758-8.439-10.139-18.5-9.317V6.396c10.061-.822 17.03 5.559 18.5 9.317m0 25.963c1.47-3.758 8.439-10.139 18.5-9.317V6.396c-10.061-.822-17.03 5.559-18.5 9.317m0 0v25.963");
}

</style>
