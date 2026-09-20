<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmh8azp6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmh8azp6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-down-box-sharp" /></template>
