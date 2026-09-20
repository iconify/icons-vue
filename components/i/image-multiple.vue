<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cacd_mhly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cacd_mhly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:image-multiple" /></template>
