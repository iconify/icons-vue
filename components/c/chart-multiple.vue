<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es_694bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es_694bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chart-multiple" /></template>
