<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knixm12od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knixm12od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cloud-upload" /></template>
