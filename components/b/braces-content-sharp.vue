<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1y6j3b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1y6j3b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:braces-content-sharp" /></template>
