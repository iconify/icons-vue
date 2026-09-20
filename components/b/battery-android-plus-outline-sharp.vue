<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqy4t3b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-plus-outline-sharp" /></template>
<style>
.zqy4t3b0l {
  fill: currentColor;
  d: path("M3 16V8zm-1 1V7h14.116v1H3v8h13.116v1zm16.5-1.5v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
