<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2_g6rcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bid-landscape-sharp" /></template>
<style>
.i2_g6rcvy {
  fill: currentColor;
  d: path("M3 21V3h18v18zM19 7.25l-6.05 6.8L9 10.1l-4 4v2.85l4-4L13.05 17L19 10.25z");
}

</style>
