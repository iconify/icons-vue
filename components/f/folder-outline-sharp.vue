<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo11a_-8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-outline-sharp" /></template>
<style>
.oo11a_-8s {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6z");
}

</style>
