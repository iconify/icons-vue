<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9iy4zb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9iy4zb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:float-left-sharp" /></template>
