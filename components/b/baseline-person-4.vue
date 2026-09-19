<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpqw5obtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-person-4" /></template>
<style>
.zpqw5obtg {
  fill: currentColor;
  d: path("M18.39 14.56C16.71 13.7 14.53 13 12 13s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 4 17.22V20h16v-2.78c0-1.12-.61-2.15-1.61-2.66M12 12c2.21 0 4-1.79 4-4V4.5c0-.83-.67-1.5-1.5-1.5c-.52 0-.98.27-1.25.67c-.27-.4-.73-.67-1.25-.67s-.98.27-1.25.67c-.27-.4-.73-.67-1.25-.67C8.67 3 8 3.67 8 4.5V8c0 2.21 1.79 4 4 4");
}

</style>
