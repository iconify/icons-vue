<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aubhryb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-manager-sharp" /></template>
<style>
.aubhryb9n {
  fill: currentColor;
  d: path("M14 22v-3.075l6.575-6.55l3.075 3.05L17.075 22zm6.575-5.6l.925-.975l-.925-.925l-.95.95zM2 20V4h8l2 2h10v2.1l-10 10V20z");
}

</style>
