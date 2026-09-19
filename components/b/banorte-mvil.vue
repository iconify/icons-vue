<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg3w15bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banorte-mvil" /></template>
<style>
.kg3w15bkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.346 13.547l-3.417 8.586c-7.177-.692-12.05-2.707-12.05-4.983c0-2.889 7.75-5.23 17.31-5.23S43.5 14.26 43.5 17.15h0c0 3.412-9.792 5.309-17.89 5.227zm-4.133 10.381l-4.807 12.064C8.82 35.042 4.5 32.735 4.5 30.17c0-3.461 7.75-6.267 17.31-6.267s17.31 2.806 17.31 6.267h0c0 2.658-4.63 5.027-11.551 5.911l-1.717-12.005");
}

</style>
