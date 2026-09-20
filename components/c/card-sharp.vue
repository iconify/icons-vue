<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfyqi8juj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfyqi8juj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card-sharp" /></template>
