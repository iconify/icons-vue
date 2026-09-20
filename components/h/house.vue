<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkm72k64t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:house" /></template>
<style>
.gkm72k64t {
  fill: currentColor;
  d: path("M5.692 19V9.946L2.604 12.25L2 11.458L12 4l4.346 3.223V5h1.885v3.639l3.788 2.819l-.603.792l-3.089-2.304V19h-4.52v-5.23h-3.615V19zm4.5-8.994h3.616q0-.704-.542-1.159q-.543-.455-1.266-.455t-1.265.455t-.543 1.159");
}

</style>
