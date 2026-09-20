<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecdxl0m7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecdxl0m7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gear" /></template>
