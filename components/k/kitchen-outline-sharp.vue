<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6jab7f2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:kitchen-outline-sharp" /></template>
<style>
.y6jab7f2n {
  fill: currentColor;
  d: path("M8 8V5h2v3zm0 9v-5h2v5zm-4 5V2h16v20zm2-2h12v-9H6zM6 9h12V4H6z");
}

</style>
