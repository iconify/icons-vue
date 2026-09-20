<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1mu82bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1mu82bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:laptop-glyph" /></template>
