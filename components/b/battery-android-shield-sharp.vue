<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v20qbbc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-shield-sharp" /></template>
<style>
.v20qbbc4w {
  fill: currentColor;
  d: path("M1 18V6h14.9L12 8q-.1 2.8.813 5.563T16.1 18zm17.5-1q-2-.725-3.25-2.95T14 9q1.025-.125 2.125-.625T18.5 7q1.275.875 2.375 1.375T23 9q0 2.825-1.25 5.05T18.5 17m0-2.225q.875-.575 1.5-1.7t.875-2.55q-.575-.2-1.162-.488T18.5 9.375z");
}

</style>
