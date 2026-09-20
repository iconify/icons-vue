<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4y5ewbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-person-32-filled" /></template>
<style>
.n4y5ewbao {
  fill: currentColor;
  d: path("M23.549 8.81a10.503 10.503 0 0 1 5.349 14.379l1.05 3.917a1.5 1.5 0 0 1-1.838 1.837l-3.915-1.049A10.46 10.46 0 0 1 19.5 29c-3.124 0-5.93-1.364-7.852-3.53a12.2 12.2 0 0 0 2.807-.128A8.46 8.46 0 0 0 19.5 27c1.486 0 2.88-.38 4.094-1.049c.226-.124.492-.157.742-.09l3.455.926l-.927-3.458a1 1 0 0 1 .09-.741A8.46 8.46 0 0 0 28 18.5a8.49 8.49 0 0 0-3.664-6.991a12 12 0 0 0-.787-2.7M12.5 3C18.299 3 23 7.701 23 13.5S18.299 24 12.5 24a10.46 10.46 0 0 1-4.695-1.106l-3.915 1.05a1.5 1.5 0 0 1-1.837-1.838l1.05-3.918A10.5 10.5 0 0 1 2 13.5C2 7.701 6.701 3 12.5 3m-3 11a2 2 0 0 0-2 2c0 2 1.5 4 5 4s5-2 5-4a2 2 0 0 0-2-2zm3-7a2.75 2.75 0 1 0 0 5.5a2.75 2.75 0 0 0 0-5.5");
}

</style>
