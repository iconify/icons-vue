<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxg1m2b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxg1m2b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:image-arrow-right" /></template>
