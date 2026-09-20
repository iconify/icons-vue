<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3knrprta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:featured-play-list-outline-sharp" /></template>
<style>
.i3knrprta {
  fill: currentColor;
  d: path("M6.5 12.5h8v-1h-8zm0-3h8v-1h-8zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
