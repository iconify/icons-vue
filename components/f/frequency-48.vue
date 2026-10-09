<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8uv-mb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8uv-mb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frequency-48" /></template>
