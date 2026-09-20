<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw1b53b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1b53b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-h-circle" /></template>
