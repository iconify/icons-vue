<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwx89utoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-plus-outline-sharp" /></template>
<style>
.uwx89utoi {
  fill: currentColor;
  d: path("M2 17V7h14.116v1H3v8h13.116v1zm16.5-1.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zm-14.115-.885v-5.23h8.73v5.23z");
}

</style>
