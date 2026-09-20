<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyq91rbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyq91rbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:device-laptop" /></template>
