<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-1r-27cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apparatus" /></template>
<style>
.n-1r-27cd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.702 22.345c0 7.211-5.845 13.057-13.056 13.057s-13.057-5.846-13.057-13.057S20.435 9.29 27.646 9.29h0c7.21 0 13.056 5.845 13.056 13.056m-13.58 19.533l-16.895-9.755v-19.51l17.04-9.847C16.284 1.026 5.648 7.968 3.076 18.917C.505 29.863 6.75 40.956 17.445 44.435s22.27-1.818 26.602-12.248z");
}

</style>
