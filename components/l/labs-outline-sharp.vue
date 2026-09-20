<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md-8hnrcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:labs-outline-sharp" /></template>
<style>
.md-8hnrcq {
  fill: currentColor;
  d: path("M12 21q-1.806 0-3.076-1.241t-1.27-3.028V7.654H6V3h12v4.654h-1.673v9.365q-.116 1.69-1.367 2.836T12 21M7 6.654h10V4H7zm7.356 12.404q.971-.943.971-2.327v-.75h-3.193v-1h3.193v-2.846h-3.192v-1h3.192V7.654H8.654v9.077q0 1.384.98 2.327Q10.617 20 12 20t2.356-.942M7 6.654V4z");
}

</style>
