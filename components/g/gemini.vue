<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eza0stbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eza0stbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gemini" /></template>
