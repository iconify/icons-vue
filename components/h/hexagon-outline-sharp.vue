<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud104up9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hexagon-outline-sharp" /></template>
<style>
.ud104up9h {
  fill: currentColor;
  d: path("m6.8 21l-5.2-9l5.2-9h10.4l5.2 9l-5.2 9zm1.15-2h8.1l4.025-7l-4.025-7h-8.1L3.9 12zM12 12");
}

</style>
