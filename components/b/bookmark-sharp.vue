<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uazgjac8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-sharp" /></template>
<style>
.uazgjac8v {
  fill: currentColor;
  d: path("M5 21V3h14v18l-7-3z");
}

</style>
