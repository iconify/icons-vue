<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vze09sf9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vze09sf9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-justify" /></template>
