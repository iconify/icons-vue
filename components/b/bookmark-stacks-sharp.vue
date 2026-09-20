<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwpay1b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-stacks-sharp" /></template>
<style>
.iwpay1b9d {
  fill: currentColor;
  d: path("M12 18L1.575 12.325l2.1-1.15L12 15.725l8.325-4.55l2.1 1.15zm0 4L1.575 16.325l2.1-1.15L12 19.725l8.325-4.55l2.1 1.15zm0-8L1 8l11-6l1 .55V7h8.175L23 8z");
}

</style>
