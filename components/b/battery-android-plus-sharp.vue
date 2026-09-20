<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3pwhbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-plus-sharp" /></template>
<style>
.hy3pwhbph {
  fill: currentColor;
  d: path("M2 17V7h14.116v2.116h-3v5.769h3V17zm16.5-1.5v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
