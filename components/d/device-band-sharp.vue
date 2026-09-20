<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvoy1ibkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:device-band-sharp" /></template>
<style>
.tvoy1ibkt {
  fill: currentColor;
  d: path("M8.866 21V8.73h-.693V6.77h.693V3h6.25v3.77h.692v1.96h-.692V21z");
}

</style>
