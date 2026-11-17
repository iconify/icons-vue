<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv04onbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewood-fill-sharp" /></template>
<style>
.cv04onbha {
  fill: currentColor;
  d: path("M5.12 4.371c.148-.374.419-.687.733-.935c.959-.756 2.485-1.102 3.672-1.269Q10.757 1.997 12 2q1.243-.003 2.475.167c1.378.194 3.818.72 4.405 2.204c-.344.523-1.3.86-1.88 1.029c-1.271.37-3.041.6-5 .6s-3.729-.23-5-.6c-.588-.172-1.534-.503-1.88-1.029M19 6v2.586l.707.707a2.414 2.414 0 0 1 0 3.414l-.707.707V19c0 .329-.098.647-.27.926c-.765 1.246-2.923 1.719-4.255 1.907q-1.232.17-2.475.167a18 18 0 0 1-2.475-.167c-1.187-.167-2.713-.513-3.672-1.269C5.364 20.178 5 19.642 5 19v-3.586l-.707-.707a2.414 2.414 0 0 1 0-3.414L5 10.586V6c.001.749 1.386 1.221 2 1.4c1.271.37 3.041.6 5 .6s3.729-.23 5-.6c.613-.179 1.999-.652 2-1.4m-8 10v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0");
}

</style>
