<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuj5j5b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuj5j5b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-x-circle" /></template>
