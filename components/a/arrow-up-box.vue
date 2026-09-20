<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbxl4wb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbxl4wb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-up-box" /></template>
