<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuy3je-si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuy3je-si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-horizontal-space-between-sharp" /></template>
