<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxcw7ob4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-copy-sharp" /></template>
<style>
.kxcw7ob4v {
  fill: currentColor;
  d: path("M7 18V2h8.5L20 6.5V18zm8-11h4l-4-4zM3 22V8h1v13h10v1z");
}

</style>
