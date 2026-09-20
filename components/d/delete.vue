<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0yupbc9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0yupbc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:delete" /></template>
