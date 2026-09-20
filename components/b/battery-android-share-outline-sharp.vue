<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf6lw9xye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-share-outline-sharp" /></template>
<style>
.pf6lw9xye {
  fill: currentColor;
  d: path("M19 8.712L22.288 12L19 15.288l-.713-.713l2.1-2.075H14.5v3h-1v-4h6.887l-2.095-2.1zM2 17V7h15.329l-1.02 1H3v8h8.116v1zm1-1V8z");
}

</style>
