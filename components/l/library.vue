<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybzc4rbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybzc4rbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:library" /></template>
