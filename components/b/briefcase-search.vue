<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7oxa7b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7oxa7b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcase-search" /></template>
