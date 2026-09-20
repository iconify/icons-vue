<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv7mdm0jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:google-wifi-outline-sharp" /></template>
<style>
.rv7mdm0jh {
  fill: currentColor;
  d: path("M4.6 10h14.8l-.275-4H4.875zm-.125 2l-.325 5h15.7l-.325-5zM5 20l-.325-1H2L3 4h18l1 15h-2.675L19 20z");
}

</style>
