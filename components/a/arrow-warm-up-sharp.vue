<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwwqzft8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-warm-up-sharp" /></template>
<style>
.jwwqzft8o {
  fill: currentColor;
  d: path("m11.5 4.864l-5.158 5.152l-.688-.689L12 2.981l6.346 6.346l-.688.714L12.5 4.883V12h-1zM11.5 17v-3h1v3zm0 4v-2h1v2z");
}

</style>
