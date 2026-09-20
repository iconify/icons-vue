<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3e13rjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detector-alarm-sharp" /></template>
<style>
.vs3e13rjl {
  fill: currentColor;
  d: path("M11.5 20v-4h1v4zm7.575-2.948l-2.838-2.813l.713-.714l2.814 2.839zm-14.15 0l-.689-.688l2.814-2.839l.714.714zm2.598-9.283l.646 1.77h7.662l.646-1.77zm-.092 2.77l-.97-2.77H4V4h16v3.77h-2.461l-1.074 2.769z");
}

</style>
