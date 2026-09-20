<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7irxxbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-plus-outline-sharp" /></template>
<style>
.v7irxxbgk {
  fill: currentColor;
  d: path("M3 16V8zm-2 2V6h15v2H3v8h13v2zm17-2v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
