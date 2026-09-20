<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_pxelbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:1k-sharp" /></template>
<style>
.v_pxelbmv {
  fill: currentColor;
  d: path("M12 15h1.5v-2.25L15.25 15H17l-2.25-3L17 9h-1.75l-1.75 2.25V9H12zm-3.5 0H10V9H7v1.5h1.5zM3 21V3h18v18z");
}

</style>
