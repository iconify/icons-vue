<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq98y6b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-card-off-sharp" /></template>
<style>
.eq98y6b3s {
  fill: currentColor;
  d: path("M22 19.15L14.85 12H20V8h-9.15l-4-4H22zM4 12h5.15l-4-4H4zm16.45 11.3l-3.3-3.3H2V4h2l2 2H3.15L.65 3.5l1.425-1.425l19.8 19.8z");
}

</style>
