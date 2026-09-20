<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epib1doug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epib1doug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:book" /></template>
