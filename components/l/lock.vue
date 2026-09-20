<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy-vk3dmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy-vk3dmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:lock" /></template>
