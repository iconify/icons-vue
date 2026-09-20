<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2e03pbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2e03pbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:colors-swatch-sharp" /></template>
