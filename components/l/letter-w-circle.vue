<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3y5tobbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3y5tobbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-w-circle" /></template>
