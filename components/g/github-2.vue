<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi8f3ubar.css';
import '../../css/u/u69h-uyii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8f3ubar"/><path class="u69h-uyii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:github-2" /></template>
