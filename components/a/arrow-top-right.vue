<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1km3rguj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-top-right" /></template>
<style>
.n1km3rguj {
  fill: currentColor;
  d: path("M6 19V8.5h11.079l-3.792-3.786L14 4l5 5l-5.006 5.006l-.707-.714L17.079 9.5H7V19z");
}

</style>
