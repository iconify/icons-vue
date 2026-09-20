<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyt7kp80q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-array-outline-sharp" /></template>
<style>
.gyt7kp80q {
  fill: currentColor;
  d: path("M15.423 19v-1H18V6h-2.577V5H19v14zM5 19V5h3.577v1H6v12h2.577v1z");
}

</style>
