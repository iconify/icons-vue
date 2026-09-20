<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azwm8ybep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-ink-highlighter-sharp" /></template>
<style>
.azwm8ybep {
  fill: currentColor;
  d: path("M2 24v-4h20v4zm1.5-6l3.15-3.15l-.75-.725V12.7L10.6 8l5.4 5.425l-4.7 4.675H9.9l-.75-.75l-.65.65zM12 6.575l5.425-5.4l5.4 5.425l-5.4 5.4z");
}

</style>
