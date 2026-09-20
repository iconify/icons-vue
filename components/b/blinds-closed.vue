<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8yol016s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blinds-closed" /></template>
<style>
.l8yol016s {
  fill: currentColor;
  d: path("M14.747 21.135q-.472 0-.802-.333q-.33-.332-.33-.802H3v-1h2V4h14v15h2v1h-5.115q0 .47-.334.802q-.333.333-.804.333M6 7.75h8.25V5H6zm9.25 0H18V5h-2.75zM6 11.5h8.25V8.75H6zm9.25 0H18V8.75h-2.75zM6 15.25h8.25V12.5H6zm9.25 0H18V12.5h-2.75zM6 19h8.25v-2.75H6zm9.25 0H18v-2.75h-2.75z");
}

</style>
