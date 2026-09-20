<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_c-fw0-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter-off-outline-sharp" /></template>
<style>
.d_c-fw0-w {
  fill: currentColor;
  d: path("m15.773 12.935l-.707-.714L19.692 7.6l-2.6-2.6l-4.626 4.627l-.708-.713l5.334-5.33L21.108 7.6zM8.293 19l4.646-4.646l-2.6-2.6L5.692 16.4zm11.469 2.177l-6.116-6.115l-4.788 4.788H7.727l-.77-.77l-1.15 1.15H3.04l2.534-2.534l-.73-.73v-1.132l4.788-4.788l-6.808-6.808l.714-.713l16.938 16.938z");
}

</style>
