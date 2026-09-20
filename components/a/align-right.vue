<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi_uomb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_uomb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-right" /></template>
