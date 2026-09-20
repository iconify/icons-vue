<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-qz1vb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:full-coverage-sharp" /></template>
<style>
.b-qz1vb7z {
  fill: currentColor;
  d: path("M3 20V8h1v11h14v1zm4-4V4h15v12zm3-4h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4z");
}

</style>
