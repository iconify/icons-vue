<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n428f-bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n428f-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-center-vertical-sharp" /></template>
