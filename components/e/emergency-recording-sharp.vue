<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on4gyrb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emergency-recording-sharp" /></template>
<style>
.on4gyrb4g {
  fill: currentColor;
  d: path("M9.98 16.5h1v-3.64l3.328 1.917l.48-.86L11.482 12l3.308-1.917l-.481-.86l-3.327 1.918V7.5h-1v3.64L6.673 9.224l-.5.86L9.481 12l-3.308 1.917l.5.86l3.308-1.918zM3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19z");
}

</style>
