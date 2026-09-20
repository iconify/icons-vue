<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t58hyebaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t58hyebaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:app-mac-sharp" /></template>
