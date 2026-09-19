<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvg6h5b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cryptocom" /></template>
<style>
.mvg6h5b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.075 7.437L11.88 17.614l23.604.016l-2.305-10.192zm-2.081 13.378L5.5 25.535l8.866 15.028H17.9l4.186-3.82V34.85l-4.345-4.067v-6.396zm18.275 3.617v6.397l-4.355 4.052l.016 1.925l4.21 3.757h3.506L42.5 25.58l-6.516-4.766zm-1.208-4.343H18.94l1.704 4.3l-.526 4.796l7.765-.012l-.487-4.784z");
}

</style>
