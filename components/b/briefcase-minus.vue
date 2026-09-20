<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5t57bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5t57bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcase-minus" /></template>
