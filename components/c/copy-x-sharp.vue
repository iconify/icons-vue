<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pge1vjbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pge1vjbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:copy-x-sharp" /></template>
