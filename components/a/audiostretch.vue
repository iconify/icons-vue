<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpst82bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiostretch" /></template>
<style>
.qpst82bfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 28.044c.743-2.011 1.228-3.833 2.676-3.806c3.09.06 2.558 7.596 5.639 7.36c5.757-.442 2.55-14.868 8.315-15.196c4.632-.265 3.393 11.148 8.027 11.373c3.362.163 3.23-7.711 6.595-7.646c2.81.054 2.45 6.422 5.256 6.595c2.091.129 3.307-3.162 4.492-4.397");
}

</style>
