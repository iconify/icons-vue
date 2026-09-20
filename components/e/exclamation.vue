<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f98ppfb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:exclamation" /></template>
<style>
.f98ppfb3v {
  fill: currentColor;
  d: path("M11.5 14.077v-8h1v8zm0 3.846v-1h1v1z");
}

</style>
