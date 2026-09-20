<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceieocbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceieocbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:dog" /></template>
