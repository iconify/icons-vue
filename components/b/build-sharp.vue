<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8weeac8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:build-sharp" /></template>
<style>
.m8weeac8a {
  fill: currentColor;
  d: path("M17.875 21.425L11.1 14.6q-.5.2-1.012.3T9 15q-2.5 0-4.25-1.75T3 9q0-.9.25-1.712t.7-1.538L7.6 9.4l1.8-1.8l-3.65-3.65q.725-.45 1.538-.7T9 3q2.5 0 4.25 1.75T15 9q0 .575-.1 1.088t-.3 1.012l6.825 6.775z");
}

</style>
