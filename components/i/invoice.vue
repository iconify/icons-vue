<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-1oojuup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1oojuup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:invoice" /></template>
