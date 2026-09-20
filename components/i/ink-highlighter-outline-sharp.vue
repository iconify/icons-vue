<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddxroxb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter-outline-sharp" /></template>
<style>
.ddxroxb0h {
  fill: currentColor;
  d: path("m13.6 13.692l-1.3-1.3l-1.3-1.3L5.692 16.4l2.6 2.6zm-1.886-3.313l1.3 1.3l1.3 1.3L19.692 7.6l-2.6-2.6zM3.039 20.23l2.534-2.535l-.73-.73v-1.132l5.809-5.809l4.015 4.016l-5.81 5.809h-1.13l-.77-.77l-1.15 1.15zm7.613-10.206l6.44-6.44L21.108 7.6l-6.44 6.44z");
}

</style>
