<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgai3o1sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:directions-alt-off-sharp" /></template>
<style>
.mgai3o1sj {
  fill: currentColor;
  d: path("M20.475 23.3L16 18.8l-4 4L1.2 12l4-4L.675 3.5L2.1 2.075l19.8 19.8zm-8.8-8.8L10.6 15.6L12 17l1.1-1.1zm7.175 1.45l-2.9-2.9L17 12l-5-5l-1.05 1.05l-2.9-2.9L12 1.2L22.8 12zM7 11v2h3.175l-2-2z");
}

</style>
