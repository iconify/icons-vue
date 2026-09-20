<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-li3u5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-plus" /></template>
<style>
.f0-li3u5i {
  fill: currentColor;
  d: path("M4.385 17q-.994 0-1.69-.695T2 14.615v-5.23q0-.994.696-1.69T4.385 7h11.73v2.116h-3v5.769h3V17zM18.5 15.5v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
