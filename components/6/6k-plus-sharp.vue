<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8um944ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:6k-plus-sharp" /></template>
<style>
.b8um944ja {
  fill: currentColor;
  d: path("M6 15h4v-3.5H7.5v-1H10V9H6zm1.5-1v-1.5h1V14zm3.5 1h1.5v-2.25L14.25 15H16l-2.25-3L16 9h-1.75l-1.75 2.25V9H11zm5.5-1h1v-1.5H19v-1h-1.5V10h-1v1.5H15v1h1.5zM3 21V3h18v18z");
}

</style>
