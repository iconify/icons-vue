<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdads5mvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdads5mvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ferris-wheel-solid" /></template>
