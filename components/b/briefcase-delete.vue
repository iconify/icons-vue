<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cemr4cbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cemr4cbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcase-delete" /></template>
