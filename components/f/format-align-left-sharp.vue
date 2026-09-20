<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhu6l4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-align-left-sharp" /></template>
<style>
.fhu6l4bta {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm0-3.75v-1h10v1zm0-3.75v-1h16v1zm0-3.75v-1h10v1zM4 5V4h16v1z");
}

</style>
