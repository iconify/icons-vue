<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2r4zdngh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2r4zdngh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:estate-sharp" /></template>
