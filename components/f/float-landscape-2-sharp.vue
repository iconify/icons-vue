<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m10txfbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:float-landscape-2-sharp" /></template>
<style>
.m10txfbrs {
  fill: currentColor;
  d: path("M12.616 14.385h5v-6h-5zM3 19V5h18v14z");
}

</style>
