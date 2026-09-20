<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szyg5_byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szyg5_byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:crop-sharp" /></template>
