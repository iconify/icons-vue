<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3g9g4pyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3g9g4pyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:computer" /></template>
