<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4e8929wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4e8929wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:fill-half" /></template>
