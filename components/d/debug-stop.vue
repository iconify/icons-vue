<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8e5vfbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e5vfbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:debug-stop" /></template>
