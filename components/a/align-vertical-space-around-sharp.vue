<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfkwqpsmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfkwqpsmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-space-around-sharp" /></template>
