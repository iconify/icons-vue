<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs374ght"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:briefcase-meal-sharp" /></template>
<style>
.sbs374ght {
  fill: currentColor;
  d: path("M3 20V7h6V4h6v3h6v13zm7-13h4V5h-4zm-.442 12v-3.596q.496-.131.834-.552q.339-.42.339-.969v-3.19h-.786v2.967h-.59v-2.968H8.57v2.968h-.59v-2.968h-.768v3.191q0 .548.329.97q.328.42.844.55V19zm6.058 0v-2.97q.496-.291.834-.985q.339-.694.339-1.612q0-1.133-.516-1.937q-.515-.804-1.234-.804q-.739 0-1.255.805q-.515.804-.515 1.942q0 .903.332 1.6q.333.697.841.992V19z");
}

</style>
