<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cga6z43xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cga6z43xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gpu-sharp" /></template>
