<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s15-9-g5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:colors-sharp" /></template>
<style>
.s15-9-g5u {
  fill: currentColor;
  d: path("m9.787 20.617l-7.404-7.404l6.636-6.63l-2.88-2.804l.78-.798l10.233 10.271zm-.02-13.286L3.86 13.258h11.834zM19.32 20q-.707 0-1.178-.493q-.472-.494-.472-1.207q0-.54.232-1.044t.599-.944l.82-1.004l.869 1.004q.361.44.596.944t.234 1.044q0 .714-.496 1.207T19.319 20");
}

</style>
