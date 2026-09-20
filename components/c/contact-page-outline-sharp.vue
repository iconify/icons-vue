<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7ukl1lgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-page-outline-sharp" /></template>
<style>
.x7ukl1lgu {
  fill: currentColor;
  d: path("M12 13.539q.633 0 1.066-.434t.434-1.066t-.434-1.067q-.433-.433-1.066-.433t-1.066.433t-.434 1.067t.434 1.066q.433.434 1.066.434m-3.5 3.384h7v-.152q0-.465-.248-.792t-.67-.52q-.61-.255-1.263-.396q-.652-.14-1.319-.14t-1.32.14t-1.263.396q-.42.193-.669.52q-.248.327-.248.792zM19 21H5V3h8.577L19 8.423zm-1-1V8.85L13.15 4H6v16zM6 20V4z");
}

</style>
