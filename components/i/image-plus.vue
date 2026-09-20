<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eerj2nbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eerj2nbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:image-plus" /></template>
