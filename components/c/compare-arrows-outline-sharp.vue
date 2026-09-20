<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrjxtxb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compare-arrows-outline-sharp" /></template>
<style>
.zrjxtxb3i {
  fill: currentColor;
  d: path("m8 18.98l-.708-.713l3.095-3.094H3v-1h7.387l-3.095-3.094l.708-.713l4.308 4.307zm8-5.365l-4.308-4.307L16 5l.708.714l-3.094 3.094H21v1h-7.386l3.094 3.094z");
}

</style>
